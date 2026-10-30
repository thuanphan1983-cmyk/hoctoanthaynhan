# Kế Hoạch & Hướng Dẫn Chi Tiết Xây Dựng Web App (PWA) Dạy Học và Luyện Thi Toán THPT — hoctoan_ThayNhan

Tài liệu này cung cấp lộ trình thực chiến từ con số 0 để xây dựng một nền tảng **Web App (Progressive Web App - PWA)** toàn diện dành cho giáo viên và học sinh môn **Toán THPT**, tích hợp 4 trụ cột cốt lõi:
1. **Phê duyệt Tài khoản & Quản lý Lớp học (LMS + Approval Gate):** Học sinh đăng ký bằng Gmail phải được Giáo viên phê duyệt mới mở khóa quyền truy cập hệ thống tự học và luyện đề.
2. **Tự học Lý thuyết & Luyện theo Dạng bài tập (5–10 bài/dạng) kèm Kiểm tra cuối bài:** Học sinh học lý thuyết trọng tâm, luyện từng dạng toán (mỗi dạng 5–10 bài), làm bài kiểm tra tổng kết nội dung vừa học, nhận thống kê lỗi sai theo dạng toán và tự động nhận phiếu bài tập khắc phục qua Gmail đăng ký.
3. **Luyện thi & Chấm bài Tự động (Trắc nghiệm + AI chấm Tự luận):** Hỗ trợ công thức $\LaTeX$, hình vẽ Toán học, trộn đề, chấm tự động và gửi bài khắc phục lỗi sai về Gmail.
4. **Học tập Tương tác (Gamification):** Flashcard công thức 3D, phòng thi đấu trực tiếp kiểu Kahoot/Quizizz và bảng xếp hạng XP/Streak.

Phương pháp tiếp cận được thiết kế theo hướng **Hybrid (Lai giữa AI Low-code và Lập trình hiện đại)**: sử dụng các công cụ AI sinh giao diện và mã nguồn (**Cursor, Bolt.new, v0.dev**) kết hợp với nền tảng Backend có sẵn (**Supabase**) giúp rút ngắn 70–80% thời gian code thủ công nhưng vẫn làm chủ hoàn toàn mã nguồn.

## 1. Kiến trúc Công nghệ Đề xuất (Tech Stack Tối Ưu & Miễn Phí Khởi Đầu)

Để đáp ứng đặc thù môn Toán THPT (công thức $\LaTeX$, hình học phẳng/không gian, bảng biến thiên, đồ thị), phân quyền duyệt học sinh và gửi bài khắc phục tự động, bộ công nghệ dưới đây là lựa chọn tối ưu nhất:

| Thành phần | Công nghệ lựa chọn | Lý do chọn & Vai trò trong hệ thống | Chi phí khởi đầu |
| :--- | :--- | :--- | :--- |
| **Giao diện (Frontend & PWA)** | **Next.js (React) + Tailwind CSS + Shadcn UI** | Tốc độ cao, hỗ trợ tốt nhất bởi các công cụ AI (v0, Bolt, Cursor); tích hợp `@ducanh2912/next-pwa` để cài thành App trên iOS/Android. | Miễn phí |
| **Hiển thị Toán & Hình học** | **KaTeX (`react-katex`) + SVG/TikZ + GeoGebra API** | Render công thức $\LaTeX$ nhanh gấp 5 lần MathJax; hiển thị sắc nét hình không gian/bảng biến thiên dạng SVG hoặc ảnh; nhúng đồ thị tương tác. | Miễn phí |
| **Cơ sở dữ liệu & Phân quyền** | **Supabase (PostgreSQL + Auth + RLS)** | Quản lý đăng ký bằng Gmail, chặn truy cập tự động bằng **Row Level Security (RLS)** nếu học sinh chưa được duyệt (`approval_status = 'pending'`), lưu trữ file và **Realtime**. | Miễn phí (Gói Free hào phóng) |
| **AI Chấm Tự Luận & Sinh Đề** | **Google Gemini API (`gemini-2.5-flash`)** | Nhận diện chữ viết tay Toán học từ ảnh chụp vở, chấm điểm từng bước giải tự luận, phân tích lỗi sai theo dạng toán và tự sinh câu hỏi tương tự để khắc phục. | Miễn phí (Tier miễn phí hoặc chi phí rất thấp) |
| **Gửi Email Tự Động** | **Nodemailer (Gmail SMTP) hoặc Resend** | Gửi email thông báo khi tài khoản học sinh được duyệt và tự động gửi thống kê lỗi sai + phiếu bài tập khắc phục thẳng về Gmail học sinh đã đăng ký. | Miễn phí (500 email/ngày với Gmail cá nhân) |
| **Triển khai (Hosting)** | **Vercel** | Đưa web lên mạng chỉ với 1 cú nhấp chuột từ GitHub, tự động cấp chứng chỉ bảo mật HTTPS (bắt buộc cho PWA). | Miễn phí |

## 2. Thiết kế Cơ sở Dữ liệu Chuẩn Hóa (Chạy ngay trên Supabase)

Bạn hãy tạo một dự án miễn phí tại **Supabase.com**, vào mục **SQL Editor**, dán toàn bộ đoạn mã SQL dưới đây và nhấn **Run**. Bản thiết kế này đã tích hợp đầy đủ **Cơ chế duyệt tài khoản học sinh (`approval_status`)**, **Phân hệ Tự học Lý thuyết & Dạng toán (5–10 bài/dạng)**, **Kiểm tra sau bài học** và **Gửi bài khắc phục qua Gmail**:

```sql
-- 1. BẢNG HỒ SƠ NGƯỜI DÙNG (Có cơ chế Duyệt tài khoản học sinh + Gamification)
CREATE TABLE public.profiles (
  id UUID REFERENCES auth.users ON DELETE CASCADE PRIMARY KEY,
  email TEXT UNIQUE NOT NULL, -- Gmail học sinh dùng để đăng ký & nhận bài khắc phục
  full_name TEXT NOT NULL,
  phone TEXT,
  school_name TEXT,
  role TEXT CHECK (role IN ('teacher', 'student')) DEFAULT 'student',
  grade SMALLINT DEFAULT 12, -- Khối lớp: 10, 11, 12
  approval_status TEXT CHECK (approval_status IN ('pending', 'approved', 'rejected')) DEFAULT 'pending', -- Học sinh mới đăng ký mặc định là 'pending' (Chờ duyệt)
  approved_by UUID REFERENCES public.profiles(id),
  approved_at TIMESTAMPTZ,
  avatar_url TEXT,
  xp_points INTEGER DEFAULT 0, -- Điểm kinh nghiệm thi đua
  streak_days INTEGER DEFAULT 0, -- Chuỗi ngày học liên tiếp
  created_at TIMESTAMPTZ DEFAULT NOW()
);

-- 2. BẢNG LỚP HỌC, THÀNH VIÊN & ĐIỂM DANH (Phân hệ LMS)
CREATE TABLE public.classes (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  name TEXT NOT NULL, -- VD: "Toán 12A1 - Luyện thi THPTQG"
  join_code TEXT UNIQUE NOT NULL, -- Mã lớp 6 ký tự cho HS nhập
  teacher_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  schedule_info TEXT,
  created_at TIMESTAMPTZ DEFAULT NOW()
);

CREATE TABLE public.class_members (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  class_id UUID REFERENCES public.classes(id) ON DELETE CASCADE,
  student_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  joined_at TIMESTAMPTZ DEFAULT NOW(),
  UNIQUE(class_id, student_id)
);

CREATE TABLE public.attendances (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  class_id UUID REFERENCES public.classes(id) ON DELETE CASCADE,
  student_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  session_date DATE DEFAULT CURRENT_DATE,
  status TEXT CHECK (status IN ('present', 'absent', 'late')) DEFAULT 'present',
  note TEXT,
  UNIQUE(class_id, student_id, session_date)
);

CREATE TABLE public.materials (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  class_id UUID REFERENCES public.classes(id) ON DELETE CASCADE,
  title TEXT NOT NULL,
  description TEXT,
  file_url TEXT, -- Link PDF/Word trên Supabase Storage
  video_url TEXT, -- Link bài giảng YouTube/Drive
  topic_tag TEXT, -- VD: "Hàm số", "Nguyên hàm - Tích phân", "Hình Oxyz"
  created_at TIMESTAMPTZ DEFAULT NOW()
);

-- 3. BẢNG NGÂN HÀNG CÂU HỎI TOÁN THPT (Hỗ trợ 4 dạng thức mới + LaTeX + Hình vẽ)
CREATE TABLE public.questions (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  creator_id UUID REFERENCES public.profiles(id),
  grade SMALLINT DEFAULT 12,
  chapter_name TEXT, -- VD: "Chương 1: Ứng dụng đạo hàm để khảo sát hàm số"
  topic_tag TEXT NOT NULL, -- VD: "Tính đơn điệu của hàm số"
  problem_type_tag TEXT, -- VD: "Dạng 1: Tìm khoảng đơn điệu từ bảng biến thiên/đồ thị"
  difficulty TEXT CHECK (difficulty IN ('nhan_biet', 'thong_hieu', 'van_dung', 'van_dung_cao')) DEFAULT 'thong_hieu',
  question_type TEXT CHECK (question_type IN ('mcq', 'true_false', 'short_answer', 'essay')) NOT NULL,
  content_latex TEXT NOT NULL, -- Nội dung đề bài chứa công thức $...$ hoặc $$...$$
  image_url TEXT, -- Link ảnh hình học / bảng biến thiên / đồ thị
  options JSONB, -- Lưu 4 phương án A,B,C,D (với mcq) hoặc 4 mệnh đề a,b,c,d (với true_false)
  correct_answer JSONB NOT NULL, -- Đáp án đúng
  solution_latex TEXT NOT NULL, -- Lời giải chi tiết chứa công thức LaTeX
  created_at TIMESTAMPTZ DEFAULT NOW()
);

-- 4. PHÂN HỆ TỰ HỌC: BÀI HỌC LÝ THUYẾT & CÁC DẠNG BÀI TẬP (MỖI DẠNG 5-10 BÀI)
CREATE TABLE public.self_study_lessons (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  grade SMALLINT DEFAULT 12,
  chapter_number SMALLINT NOT NULL,
  chapter_title TEXT NOT NULL, -- VD: "Chương I. Ứng dụng đạo hàm"
  lesson_order SMALLINT NOT NULL,
  title TEXT NOT NULL, -- VD: "Bài 1. Tính đơn điệu và cực trị của hàm số"
  theory_content_latex TEXT NOT NULL, -- Toàn bộ lý thuyết trọng tâm, định lý, chú ý (có công thức LaTeX)
  theory_video_url TEXT, -- Video bài giảng lý thuyết (nếu có)
  summary_image_url TEXT, -- Sơ đồ tư duy / Bảng tóm tắt công thức
  quiz_duration_minutes INTEGER DEFAULT 30, -- Thời gian làm bài kiểm tra sau bài học
  quiz_question_ids UUID[] NOT NULL, -- Danh sách câu hỏi cho Bài kiểm tra đánh giá cuối bài học
  pass_score NUMERIC(4,2) DEFAULT 7.0, -- Điểm đạt yêu cầu để qua bài mới
  created_at TIMESTAMPTZ DEFAULT NOW()
);

CREATE TABLE public.lesson_problem_types (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  lesson_id UUID REFERENCES public.self_study_lessons(id) ON DELETE CASCADE,
  type_order SMALLINT NOT NULL, -- Thứ tự dạng: Dạng 1, Dạng 2, Dạng 3...
  type_title TEXT NOT NULL, -- VD: "Dạng 1: Xác định khoảng đồng biến, nghịch biến của hàm số cho bởi công thức"
  method_latex TEXT NOT NULL, -- Phương pháp giải, các bước thực hiện & mẹo giải nhanh (LaTeX)
  example_latex TEXT, -- Ví dụ mẫu có lời giải chi tiết
  practice_question_ids UUID[] NOT NULL, -- Mảng gồm 5 đến 10 câu hỏi luyện tập thuộc đúng dạng này (Ràng buộc 5-10 bài)
  created_at TIMESTAMPTZ DEFAULT NOW(),
  CONSTRAINT check_practice_count CHECK (
    array_length(practice_question_ids, 1) BETWEEN 5 AND 10
  )
);

-- 5. BẢNG THEO DÕI TIẾN ĐỘ TỰ HỌC & KẾT QUẢ KIỂM TRA SAU BÀI HỌC CỦA HỌC SINH
CREATE TABLE public.student_lesson_progress (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  student_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  lesson_id UUID REFERENCES public.self_study_lessons(id) ON DELETE CASCADE,
  is_theory_completed BOOLEAN DEFAULT FALSE, -- Đã học xong phần Lý thuyết chưa
  completed_problem_types JSONB DEFAULT '{}'::jsonb, -- Lưu kết quả làm 5-10 bài của từng Dạng (VD: {"type_id_1": {"completed": 8, "total": 8, "score": 9.0}})
  is_quiz_unlocked BOOLEAN DEFAULT FALSE, -- Mở khóa bài kiểm tra khi đã hoàn thành lý thuyết & các dạng bài tập
  quiz_score NUMERIC(4,2), -- Điểm bài kiểm tra kiến thức vừa học
  quiz_wrong_by_type JSONB, -- Thống kê lỗi sai theo từng dạng toán trong bài vừa học
  remedial_email_sent BOOLEAN DEFAULT FALSE, -- Đã gửi thống kê lỗi sai & bài khắc phục về Gmail đăng ký chưa
  updated_at TIMESTAMPTZ DEFAULT NOW(),
  UNIQUE(student_id, lesson_id)
);

-- 6. BẢNG ĐỀ KIỂM TRA CHUNG & BÀI NỘP CỦA HỌC SINH
CREATE TABLE public.exams (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  class_id UUID REFERENCES public.classes(id) ON DELETE CASCADE,
  lesson_id UUID REFERENCES public.self_study_lessons(id) ON DELETE SET NULL, -- Gắn với bài tự học (nếu là bài kiểm tra sau bài học)
  title TEXT NOT NULL,
  duration_minutes INTEGER DEFAULT 45,
  question_ids UUID[] NOT NULL,
  shuffle_questions BOOLEAN DEFAULT TRUE,
  shuffle_options BOOLEAN DEFAULT TRUE,
  due_date TIMESTAMPTZ,
  created_at TIMESTAMPTZ DEFAULT NOW()
);

CREATE TABLE public.exam_submissions (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  exam_id UUID REFERENCES public.exams(id) ON DELETE CASCADE,
  student_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  answers JSONB NOT NULL,
  objective_score NUMERIC(4,2) DEFAULT 0,
  essay_score NUMERIC(4,2) DEFAULT 0,
  total_score NUMERIC(4,2) DEFAULT 0,
  mistake_stats_by_type JSONB, -- Thống kê chi tiết số câu sai theo từng Dạng toán / Chuyên đề
  ai_feedback JSONB,
  remedial_email_sent BOOLEAN DEFAULT FALSE,
  submitted_at TIMESTAMPTZ DEFAULT NOW()
);

-- 7. BẢNG LƯU LỖI SAI & PHIẾU BÀI TẬP KHẮC PHỤC (Gửi qua Gmail học sinh đăng ký)
CREATE TABLE public.remedial_assignments (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  submission_id UUID REFERENCES public.exam_submissions(id) ON DELETE CASCADE,
  lesson_id UUID REFERENCES public.self_study_lessons(id) ON DELETE SET NULL,
  student_id UUID REFERENCES public.profiles(id) ON DELETE CASCADE,
  weak_topics TEXT[] NOT NULL, -- Các dạng bài tập / chuyên đề học sinh bị sai
  remedial_questions JSONB NOT NULL, -- Danh sách câu hỏi luyện lại để khắc phục lỗi sai
  is_completed BOOLEAN DEFAULT FALSE,
  score NUMERIC(4,2),
  sent_to_email TEXT NOT NULL, -- Gmail học sinh đã đăng ký
  created_at TIMESTAMPTZ DEFAULT NOW()
);

-- 8. BẢNG FLASHCARD & PHÒNG THI ĐẤU TRỰC TIẾP (Phân hệ Gamification)
CREATE TABLE public.flashcards (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  grade SMALLINT DEFAULT 12,
  topic_tag TEXT NOT NULL,
  front_latex TEXT NOT NULL,
  back_latex TEXT NOT NULL,
  image_url TEXT
);

CREATE TABLE public.live_rooms (
  id UUID DEFAULT gen_random_uuid() PRIMARY KEY,
  room_pin TEXT UNIQUE NOT NULL,
  host_id UUID REFERENCES public.profiles(id),
  exam_id UUID REFERENCES public.exams(id),
  status TEXT CHECK (status IN ('waiting', 'playing', 'finished')) DEFAULT 'waiting',
  current_question_index INTEGER DEFAULT 0,
  created_at TIMESTAMPTZ DEFAULT NOW()
);

-- 9. BẢO MẬT PHÂN QUYỀN (ROW LEVEL SECURITY): CHỈ HỌC SINH ĐÃ ĐƯỢC DUYỆT MỚI XEM ĐƯỢC BÀI TỰ HỌC
ALTER TABLE public.self_study_lessons ENABLE ROW LEVEL SECURITY;
ALTER TABLE public.lesson_problem_types ENABLE ROW LEVEL SECURITY;

CREATE POLICY "Chi giao vien hoac hoc sinh da duoc duyet moi xem duoc bai tu hoc"
ON public.self_study_lessons FOR SELECT
USING (
  EXISTS (
    SELECT 1 FROM public.profiles
    WHERE profiles.id = auth.uid()
    AND (profiles.role = 'teacher' OR profiles.approval_status = 'approved')
  )
);

CREATE POLICY "Chi giao vien hoac hoc sinh da duoc duyet moi xem duoc cac dang bai tap"
ON public.lesson_problem_types FOR SELECT
USING (
  EXISTS (
    SELECT 1 FROM public.profiles
    WHERE profiles.id = auth.uid()
    AND (profiles.role = 'teacher' OR profiles.approval_status = 'approved')
  )
);
```

## 3. Chi Tiết Luồng Nghiệp Vụ Mới: Duyệt Học Sinh & Lộ Trình Tự Học Khép Kín

Để đảm bảo học sinh học thực chất và chỉ những học sinh được bạn cho phép mới vào được kho bài giảng tự học, hệ thống vận hành theo 2 luồng chặt chẽ sau:

### 3.1. Luồng Đăng ký & Giáo viên Phê duyệt Tài khoản (`Approval Gate`)

1. **Bước 1 — Học sinh Đăng ký bằng Gmail:**
   - Học sinh chọn **"Đăng ký bằng Google (Gmail)"** hoặc điền form (Gmail, Họ và tên, Khối lớp 10/11/12, Trường, Số điện thoại).
   - Hệ thống tự động lưu tài khoản vào bảng `profiles` với trạng thái `approval_status = 'pending'`.
2. **Bước 2 — Màn hình Chờ duyệt (Khoá tính năng Tự học):**
   - Khi học sinh đăng nhập nhưng trạng thái vẫn là `'pending'`, toàn bộ menu **Tự học Lý thuyết & Dạng bài tập**, **Làm bài kiểm tra** sẽ bị khóa (hiển thị biểu tượng ổ khóa 🔒).
   - Màn hình hiện thông báo thân thiện: *"Tài khoản của em đã đăng ký thành công với Gmail `...` và đang chờ Giáo viên phê duyệt. Ngay khi Giáo viên duyệt, em sẽ nhận được email thông báo và mở khóa toàn bộ lộ trình Tự học!"*.
3. **Bước 3 — Giáo viên Phê duyệt 1-chạm trên Dashboard:**
   - Giáo viên vào mục **"Duyệt học sinh đăng ký mới"**, kiểm tra tên và Gmail của học sinh, nhấn nút **"Duyệt (Approve)"** (hoặc chọn nhiều học sinh và bấm **"Duyệt tất cả"**).
   - Hệ thống đổi `approval_status = 'approved'`, mở khóa ngay lập tức các tính năng tự học và tự động gửi 1 email chào mừng về Gmail đăng ký của học sinh.

### 3.2. Luồng Học sinh Tự học Lý thuyết -> Luyện các Dạng bài tập (5–10 bài/dạng) -> Kiểm tra -> Gửi Gmail khắc phục

Mỗi bài học trong phân hệ **Tự học** được thiết kế theo cấu trúc sư phạm 4 bước tuần tự (học sinh phải hoàn thành bước trước mới mở khóa bước sau):

| Bước tự học | Nội dung hiển thị trên màn hình Học sinh | Điều kiện hoàn thành & Mở khóa bước tiếp theo |
| :--- | :--- | :--- |
| **Bước 1: Học Lý thuyết trọng tâm** | - Tóm tắt định nghĩa, định lý, tính chất, công thức đóng khung (hiển thị bằng $\LaTeX$ sắc nét).<br>- Hình vẽ minh họa, bảng biến thiên mẫu hoặc video bài giảng ngắn của giáo viên. | Học sinh đọc hết lý thuyết và bấm nút **"Đã nắm vững lý thuyết"** $\rightarrow$ Mở khóa khu vực **Các dạng bài tập**. |
| **Bước 2: Luyện từng Dạng bài tập (Mỗi dạng 5–10 bài)** | - Chia thành các Tab rõ ràng: **Dạng 1, Dạng 2, Dạng 3...**<br>- Đầu mỗi dạng có khung **Phương pháp giải & Ví dụ mẫu**.<br>- Bên dưới là **danh sách 5–10 bài tập tự luyện** đúng dạng đó. Học sinh làm từng bài, hệ thống chấm ngay và hiện lời giải chi tiết sau khi nộp từng dạng. | Học sinh phải hoàn thành các dạng bài tập trong bài (ví dụ: đạt tối thiểu **70% số câu đúng** ở mỗi dạng trong 5–10 bài) $\rightarrow$ Hệ thống tự động **Mở khóa Bài kiểm tra cuối bài học**. |
| **Bước 3: Bài kiểm tra đánh giá kiến thức vừa học** | - Bài kiểm tra có đồng hồ đếm ngược (15–30 phút), tổng hợp câu hỏi quét qua tất cả các dạng vừa học ở Bước 2 (gồm cả Trắc nghiệm 4 lựa chọn, Đúng/Sai, Trả lời ngắn và Tự luận). | Học sinh bấm **"Nộp bài kiểm tra"** $\rightarrow$ Chuyển sang Bước 4. |
| **Bước 4: Thống kê lỗi sai & Gửi bài khắc phục về Gmail** | - Hệ thống chấm điểm ngay, lập **Bảng thống kê lỗi sai theo từng Dạng bài tập** (VD: *Dạng 1: Đúng 4/4; Dạng 2: Sai 3/5 câu — Lỗi quên tìm ĐKXĐ*).<br>- AI Gemini tạo **Phiếu bài tập khắc phục lỗi sai** (chỉ tập trung vào các dạng bị sai) và **gửi tự động về Gmail học sinh đã đăng ký**. | Học sinh mở Gmail hoặc bấm trực tiếp từ thông báo để làm bài khắc phục lỗi sai và mở khóa Bài học tiếp theo. |

## 4. Lộ trình Thực hiện Chi tiết Từng Giai đoạn (6 Tuần)

### Giai đoạn 1: Thiết lập Supabase, Đăng ký Gmail & Cổng Phê duyệt Học sinh (Tuần 1)

1. **Khởi tạo Database & Row Level Security (RLS):**
   - Chạy toàn bộ mã SQL ở Mục 2 trên Supabase.
   - Bật tính năng **Google Auth** hoặc **Email/Password Auth** trên Supabase để học sinh đăng ký bằng đúng địa chỉ Gmail thật của mình.
2. **Xây dựng Cổng Phê duyệt (Approval Gate):**
   - Tạo trang `/pending-approval` cho học sinh mới đăng ký.
   - Tạo trang `/teacher/approvals` cho giáo viên xem danh sách học sinh chờ duyệt (`approval_status = 'pending'`), có nút **Duyệt** và **Từ chối**.

### Giai đoạn 2: Xây dựng Phân hệ Tự học Lý thuyết & Các Dạng Bài Tập (Tuần 2)

1. **Trang Quản trị Bài tự học cho Giáo viên (`/teacher/self-study`):**
   - Giáo viên tạo Bài học mới $\rightarrow$ Nhập nội dung **Lý thuyết ($\LaTeX$)** $\rightarrow$ Thêm lần lượt **Dạng 1, Dạng 2, Dạng 3...**
   - Ở mỗi Dạng, giáo viên nhập **Phương pháp giải** và chọn (hoặc dán nhanh) **5 đến 10 câu hỏi** từ Ngân hàng câu hỏi vào dạng đó.
   - Cuối cùng, giáo viên chọn bộ câu hỏi cho **Bài kiểm tra đánh giá cuối bài học**.
2. **Giao diện Tự học Từng bước cho Học sinh (`/student/self-study/[lessonId]`):**
   - Hiển thị thanh tiến trình (Progress Bar) 3 chặng: `1. Lý thuyết` $\rightarrow$ `2. Luyện các dạng (5-10 bài/dạng)` $\rightarrow$ `3. Kiểm tra kiến thức vừa học`.
   - Khi học sinh đang làm 5–10 bài của từng dạng, cho phép xem gợi ý từng bước để hiểu sâu phương pháp trước khi bước vào bài kiểm tra thật.

### Giai đoạn 3: Ngân hàng Câu hỏi, Trộn đề & Kiểm tra Sau Bài Học (Tuần 3)

1. **Hiển thị công thức Toán ($\LaTeX$) và Hình vẽ:**
   - Tích hợp `katex` và `react-katex` hiển thị công thức `$ ... $` và `$$ ... $$`.
   - Hỗ trợ dán ảnh hình học không gian, bảng biến thiên, đồ thị trực tiếp từ Clipboard (`Ctrl + V`).
2. **Chấm tự động 4 dạng thức Toán THPT:**
   - Chấm tự động Trắc nghiệm 4 lựa chọn, Đúng/Sai 4 ý, Trả lời ngắn và gắn thẻ từng câu hỏi với `problem_type_tag` (Dạng 1, Dạng 2...) để sau khi học sinh nộp bài kiểm tra cuối bài học, hệ thống biết chính xác học sinh đang yếu ở dạng toán nào.

### Giai đoạn 4: Thống kê Lỗi sai, AI Chấm Tự luận & Tự động Gửi Gmail Khắc phục (Tuần 4)

1. **Phân tích lỗi sai theo Dạng bài vừa học:**
   - Ngay khi học sinh nộp Bài kiểm tra cuối bài tự học (hoặc đề thi chung), hệ thống gom nhóm tất cả các câu làm sai theo từng **Dạng bài tập (`problem_type_tag`)**.
2. **AI Gemini Sinh Phiếu Bài Tập Khắc Phục & Gửi về Gmail Đăng Ký:**
   - Hệ thống lấy địa chỉ `email` trong bảng `profiles` (Gmail học sinh đã dùng khi đăng ký và được giáo viên duyệt).
   - Gọi Gemini API (`gemini-2.5-flash`) phân tích nguyên nhân sai ở từng dạng, tạo bộ câu hỏi khắc phục kèm phương pháp giải và gửi thẳng về Gmail của học sinh qua **Nodemailer**.

### Giai đoạn 5: Quản lý Lớp học (LMS) & Học tập Tương tác / Gamification (Tuần 5)

1. **Quản lý Lớp & Điểm danh QR:** Điểm danh nhanh trên lớp, giao bài tập về nhà và theo dõi bảng tiến độ tự học của cả lớp (ai đã học xong lý thuyết, ai đã làm hết các dạng bài tập, ai đã qua bài kiểm tra cuối bài).
2. **Flashcard 3D & Đấu trường Trực tiếp (Kahoot/Quizizz):** Ôn tập công thức Toán bằng thẻ lật 3D và mở phòng thi đấu trực tiếp qua **Supabase Realtime**.

### Giai đoạn 6: Đóng gói PWA & Triển khai lên Vercel (Tuần 6)

- Cấu hình `manifest.json` để học sinh cài Web App ra màn hình chính điện thoại (iOS/Android) và triển khai miễn phí lên **Vercel**.

## 5. Mã Nguồn Mẫu Cốt Lõi (Sẵn sàng tích hợp vào dự án)

### 5.1. Component Chặn Học Sinh Chưa Được Duyệt (`components/ApprovalGuard.tsx`)

Đặt Component này bọc bên ngoài các trang **Tự học** để đảm bảo học sinh đăng ký xong phải được Giáo viên duyệt mới sử dụng được:

```tsx
"use client";
import React from "react";
import { Lock, Clock, CheckCircle2 } from "lucide-react";

interface ApprovalGuardProps {
  profile: {
    full_name: string;
    email: string;
    role: "teacher" | "student";
    approval_status: "pending" | "approved" | "rejected";
  };
  children: React.ReactNode;
}

export default function ApprovalGuard({ profile, children }: ApprovalGuardProps) {
  // Giáo viên hoặc học sinh đã được duyệt thì hiển thị đầy đủ tính năng Tự học
  if (profile.role === "teacher" || profile.approval_status === "approved") {
    return <>{children}</>;
  }

  // Nếu học sinh vừa đăng ký và đang chờ duyệt (pending)
  return (
    <div className="max-w-xl mx-auto mt-16 p-8 bg-white rounded-2xl shadow-lg border border-amber-200 text-center">
      <div className="w-16 h-16 bg-amber-100 text-amber-600 rounded-full flex items-center justify-center mx-auto mb-4">
        <Clock className="w-8 h-8" />
      </div>
      <h2 className="text-2xl font-bold text-slate-800 mb-2">
        Tài khoản đang chờ Giáo viên phê duyệt
      </h2>
      <p className="text-slate-600 mb-6 leading-relaxed">
        Chào <strong>{profile.full_name}</strong>! Em đã đăng ký thành công với Gmail{" "}
        <span className="font-semibold text-blue-600">{profile.email}</span>.
        Để mở khóa chức năng <strong>Tự học Lý thuyết, Luyện các dạng bài tập (5–10 bài/dạng) và Kiểm tra</strong>, tài khoản của em cần được Giáo viên xác nhận.
      </p>
      <div className="bg-slate-50 p-4 rounded-xl text-left text-sm text-slate-600 space-y-2 border border-slate-200">
        <div className="flex items-center gap-2">
          <CheckCircle2 className="w-4 h-4 text-emerald-600 shrink-0" />
          <span>Đã ghi nhận Gmail nhận phiếu bài tập khắc phục lỗi sai: <strong>{profile.email}</strong></span>
        </div>
        <div className="flex items-center gap-2">
          <Lock className="w-4 h-4 text-amber-600 shrink-0" />
          <span>Ngay khi Giáo viên bấm Duyệt, hệ thống sẽ gửi thông báo về Gmail và mở khóa toàn bộ bài học cho em.</span>
        </div>
      </div>
    </div>
  );
}
```

### 5.2. API Chấm Bài Kiểm Tra Sau Khi Tự Học + Thống Kê Lỗi Sai Theo Dạng + Gửi Về Gmail Đăng Ký (`app/api/self-study/submit-quiz/route.ts`)

Đoạn API dưới đây xử lý trọn vẹn bước cuối của quá trình Tự học: **Kiểm tra học sinh đã được duyệt chưa -> Chấm bài kiểm tra cuối bài học -> Thống kê lỗi sai theo từng Dạng toán vừa học -> Gọi AI tạo bài tập khắc phục -> Gửi thẳng về Gmail đăng ký của học sinh**:

```typescript
import { NextResponse } from "next/server";
import { GoogleGenAI } from "@google/genai";
import nodemailer from "nodemailer";

const ai = new GoogleGenAI({ apiKey: process.env.GEMINI_API_KEY });

export async function POST(req: Request) {
  try {
    const {
      studentProfile, // Chứa email đã đăng ký, full_name, approval_status
      lessonTitle,    // Tên bài tự học (VD: "Bài 1: Tính đơn điệu và cực trị của hàm số")
      quizResults,    // Danh sách câu trả lời kèm problem_type_tag (Dạng 1, Dạng 2...)
      essayAnswer,    // Bài làm tự luận (nếu có)
      appBaseUrl
    } = await req.json();

    // 1. KIỂM TRA QUYỀN: HỌC SINH PHẢI ĐƯỢC DUYỆT MỚI ĐƯỢC CHẤM & NHẬN BÀI TỰ HỌC
    if (studentProfile.role === "student" && studentProfile.approval_status !== "approved") {
      return NextResponse.json(
        { error: "Tài khoản chưa được Giáo viên phê duyệt chức năng tự học." },
        { status: 403 }
      );
    }

    // 2. THỐNG KÊ LỖI SAI THEO TỪNG DẠNG BÀI TẬP VỪA HỌC
    const statsByType: Record<string, { total: number; wrong: number; wrongQuestions: any[] }> = {};
    let correctCount = 0;

    for (const item of quizResults) {
      const typeName = item.problem_type_tag || "Kiến thức chung";
      if (!statsByType[typeName]) {
        statsByType[typeName] = { total: 0, wrong: 0, wrongQuestions: [] };
      }
      statsByType[typeName].total += 1;

      if (item.isCorrect) {
        correctCount += 1;
      } else {
        statsByType[typeName].wrong += 1;
        statsByType[typeName].wrongQuestions.push({
          content_latex: item.content_latex,
          student_answer: item.student_answer,
          correct_answer: item.correct_answer,
          solution_latex: item.solution_latex
        });
      }
    }

    const objectiveScore = Number(((correctCount / quizResults.length) * 10).toFixed(2));

    // 3. GỌI GEMINI AI PHÂN TÍCH LỖI SAI THEO DẠNG TOÁN & TẠO BÀI TẬP KHẮC PHỤC
    const prompt = `
      Học sinh "${studentProfile.full_name}" vừa hoàn thành phần Tự học Lý thuyết, luyện các dạng bài tập và làm Bài kiểm tra cuối bài: "${lessonTitle}".
      Dưới đây là thống kê lỗi sai theo từng dạng bài tập của học sinh:
      ${JSON.stringify(statsByType)}

      Hãy thực hiện:
      1. Nhận xét ngắn gọn ưu điểm và chỉ rõ học sinh đang bị hổng ở Dạng bài tập nào, nguyên nhân sai thường gặp ở các câu đó.
      2. Với mỗi Dạng bài tập mà học sinh làm sai (wrong > 0), hãy tạo ra 3 câu hỏi bài tập khắc phục lỗi sai tương ứng với dạng đó (có công thức Toán bọc trong dấu $...$, 4 phương án A, B, C, D, đáp án đúng và lời giải từng bước).

      Trả về đúng định dạng JSON:
      {
        "overallAnalysis": "Nhận xét tổng quan...",
        "weakProblemTypes": ["Tên dạng bài bị sai 1", "Tên dạng bài bị sai 2"],
        "remedialByType": [
          {
            "problemType": "Tên dạng bài",
            "mistakeReason": "Nguyên nhân học sinh làm sai ở dạng này...",
            "questions": [
              {
                "question": "Nội dung câu hỏi...",
                "options": ["A. ...", "B. ...", "C. ...", "D. ..."],
                "correctAnswer": "A",
                "explanation": "Hướng dẫn giải khắc phục..."
              }
            ]
          }
        ]
      }
    `;

    const response = await ai.models.generateContent({
      model: "gemini-2.5-flash",
      contents: prompt,
      config: { responseMimeType: "application/json" }
    });

    const aiAnalysis = JSON.parse(response.text || "{}");

    // 4. GỬI THỐNG KÊ LỖI SAI & BÀI TẬP KHẮC PHỤC VỀ GMAIL ĐĂNG KÝ CỦA HỌC SINH
    const transporter = nodemailer.createTransport({
      service: "gmail",
      auth: {
        user: process.env.TEACHER_GMAIL_USER,
        pass: process.env.TEACHER_GMAIL_APP_PASSWORD
      }
    });

    // Tạo bảng HTML thống kê kết quả theo từng dạng toán
    const statsTableRows = Object.entries(statsByType)
      .map(
        ([type, data]) => `
        <tr>
          <td style="padding: 8px 12px; border: 1px solid #cbd5e1;">${type}</td>
          <td style="padding: 8px 12px; border: 1px solid #cbd5e1; text-align: center;">${data.total - data.wrong}/${data.total}</td>
          <td style="padding: 8px 12px; border: 1px solid #cbd5e1; text-align: center; color: ${data.wrong > 0 ? "#dc2626" : "#16a34a"}; font-weight: bold;">
            ${data.wrong > 0 ? `Sai ${data.wrong} câu (Cần khắc phục)` : "Đã nắm vững"}
          </td>
        </tr>
      `
      )
      .join("");

    // Tạo danh sách bài tập khắc phục theo từng dạng bị sai
    const remedialHtml = (aiAnalysis.remedialByType || [])
      .map(
        (group: any) => `
        <div style="margin-top: 20px; padding: 16px; background: #fffbeb; border-left: 4px solid #f59e0b; border-radius: 8px;">
          <h4 style="margin: 0 0 8px 0; color: #b45309;">Khắc phục: ${group.problemType}</h4>
          <p style="margin: 0 0 12px 0; font-size: 14px; color: #78350f;"><strong>Lỗi cần tránh:</strong> ${group.mistakeReason}</p>
          ${(group.questions || [])
            .map(
              (q: any, i: number) => `
              <div style="background: #ffffff; padding: 12px; border-radius: 6px; margin-bottom: 10px; border: 1px solid #fde68a;">
                <p style="margin: 0 0 8px 0;"><strong>Bài khắc phục ${i + 1}:</strong> ${q.question}</p>
                <ul style="margin: 0 0 8px 0; padding-left: 20px;">
                  ${(q.options || []).map((opt: string) => `<li>${opt}</li>`).join("")}
                </ul>
                <p style="margin: 0; font-size: 13px; color: #475569;"><em>Đáp án: <strong>${q.correctAnswer}</strong> — ${q.explanation}</em></p>
              </div>
            `
            )
            .join("")}
        </div>
      `
      )
      .join("");

    await transporter.sendMail({
      from: `"Hệ thống Tự Học Toán THPT" <${process.env.TEACHER_GMAIL_USER}>`,
      to: studentProfile.email, // Gửi đúng về Gmail mà học sinh đã đăng ký tài khoản
      subject: `[Kết quả Tự học & Bài tập khắc phục] - ${lessonTitle}`,
      html: `
        <div style="font-family: Arial, sans-serif; max-width: 680px; margin: 0 auto; color: #1e293b; line-height: 1.6;">
          <h2 style="color: #1d4ed8;">Chúc mừng ${studentProfile.full_name} đã hoàn thành bài tự học!</h2>
          <p>Bài học: <strong>${lessonTitle}</strong> — Điểm kiểm tra kiến thức vừa học: <strong style="color: #2563eb; font-size: 18px;">${objectiveScore}/10 điểm</strong></p>

          <h3>1. Thống kê mức độ nắm vững theo từng Dạng bài tập</h3>
          <table style="width: 100%; border-collapse: collapse; margin-bottom: 16px;">
            <thead>
              <tr style="background: #f1f5f9;">
                <th style="padding: 8px 12px; border: 1px solid #cbd5e1; text-align: left;">Dạng bài tập</th>
                <th style="padding: 8px 12px; border: 1px solid #cbd5e1; text-align: center;">Số câu đúng</th>
                <th style="padding: 8px 12px; border: 1px solid #cbd5e1; text-align: center;">Đánh giá</th>
              </tr>
            </thead>
            <tbody>
              ${statsTableRows}
            </tbody>
          </table>

          <p><strong>Nhận xét chuyên môn:</strong> ${aiAnalysis.overallAnalysis || ""}</p>

          <h3>2. Bài tập khắc phục lỗi sai dành riêng cho em</h3>
          <p>Hệ thống đã tổng hợp các bài tập tương tự đúng vào những dạng toán em vừa làm sai để em rèn luyện lại:</p>
          ${remedialHtml || "<p style='color: #16a34a; font-weight: bold;'>Tuyệt vời! Em không mắc lỗi sai nào trong bài kiểm tra này.</p>"}

          <div style="text-align: center; margin-top: 28px;">
            <a href="${appBaseUrl}/student/remedial" style="background: #2563eb; color: #ffffff; padding: 12px 24px; text-decoration: none; border-radius: 6px; font-weight: bold;">
              Vào Web App nộp bài khắc phục & Học bài tiếp theo
            </a>
          </div>
        </div>
      `
    });

    return NextResponse.json({
      success: true,
      objectiveScore,
      statsByType,
      aiAnalysis,
      sentToEmail: studentProfile.email
    });
  } catch (error: any) {
    return NextResponse.json({ success: false, error: error.message }, { status: 500 });
  }
}
```

## 6. Bộ Câu Lệnh Prompt Mẫu (Copy-Paste vào AI để Tạo App Nhanh)

Bạn có thể copy nguyên văn các câu lệnh (Prompt) dưới đây dán vào **v0.dev**, **Bolt.new** hoặc **Cursor** để AI tự động sinh ra toàn bộ giao diện và logic cho bạn:

### Prompt 1 — Tạo Phân hệ Học Sinh Tự Học (Lý thuyết -> Các dạng bài tập 5–10 bài -> Kiểm tra cuối bài) & Cổng Duyệt Tài Khoản
> "Hãy thiết kế cho tôi phân hệ **Tự học Toán THPT & Phê duyệt học sinh** bằng Next.js (App Router), Tailwind CSS, Lucide Icons và Shadcn UI, có hỗ trợ hiển thị công thức Toán học bằng KaTeX (`$ ... $`). Hệ thống gồm 3 màn hình liên kết chặt chẽ:
> 1. **Màn hình Đăng ký & Chờ phê duyệt (Approval Gate)**: Học sinh đăng ký bằng Gmail, Họ tên, Khối lớp (10, 11, 12) và Trường học. Sau khi đăng ký, nếu `approval_status === 'pending'`, hiển thị màn hình thông báo tài khoản đang chờ Giáo viên phê duyệt và khóa các menu Tự học. Kèm theo một tab dành cho Giáo viên (**Quản lý phê duyệt học sinh**) cho phép xem danh sách học sinh vừa đăng ký và bấm 'Duyệt' (Approve) hoặc 'Duyệt tất cả' để mở khóa quyền tự học cho học sinh.
> 2. **Màn hình Tự học theo Bài của Học sinh (3 bước tuần tự)**:
>    - **Bước 1 (Lý thuyết trọng tâm)**: Hiển thị đầy đủ định nghĩa, định lý, công thức đóng khung (LaTeX), bảng biến thiên/hình vẽ minh họa và nút 'Đã hiểu lý thuyết -> Chuyển sang luyện Dạng bài tập'.
>    - **Bước 2 (Luyện tập theo từng Dạng toán - Mỗi dạng 5 đến 10 bài)**: Hiển thị các tab Dạng 1, Dạng 2, Dạng 3... Trong mỗi dạng có hộp 'Phương pháp giải & Ví dụ mẫu', bên dưới là danh sách từ 5 đến 10 bài tập trắc nghiệm/trả lời ngắn của dạng đó. Học sinh làm từng câu, xem đáp án/lời giải chi tiết và có thanh tiến độ hoàn thành từng dạng (VD: Đã hoàn thành 8/8 bài Dạng 1). Khi hoàn thành đủ các dạng thì mở khóa nút 'Làm bài kiểm tra cuối bài học'.
>    - **Bước 3 (Bài kiểm tra đánh giá nội dung vừa học)**: Có đồng hồ đếm ngược, tổng hợp các câu hỏi thuộc các dạng vừa học.
> 3. **Màn hình Thống kê lỗi sai & Gửi bài khắc phục về Gmail**: Ngay sau khi nộp bài kiểm tra cuối bài học, hiển thị bảng thống kê số câu đúng/sai theo từng Dạng toán (Dạng 1, Dạng 2, Dạng 3...), chỉ rõ dạng nào bị hổng, hiển thị thông báo 'Đã gửi phiếu bài tập khắc phục lỗi sai về Gmail đăng ký của em' kèm danh sách các câu hỏi khắc phục để học sinh làm lại ngay."

### Prompt 2 — Tạo Giao diện Tổng thể LMS, Làm Đề Thi Chuẩn Mới & Gamification
> "Hãy thiết kế thêm cho ứng dụng Toán THPT 3 màn hình:
> 1. **Dashboard Giáo viên**: Thống kê sĩ số lớp, số học sinh chờ duyệt tài khoản, tiến độ tự học của từng học sinh (ai đã học lý thuyết, ai đã làm xong các dạng 5–10 bài, điểm kiểm tra cuối bài), và danh sách các dạng toán học sinh hay sai nhất.
> 2. **Màn hình Làm đề thi chuẩn cấu trúc mới**: Hỗ trợ 4 phần: Phần I (Trắc nghiệm 4 lựa chọn A,B,C,D), Phần II (Đúng/Sai với 4 ý a,b,c,d trong mỗi câu), Phần III (Điền đáp án số trả lời ngắn), và Phần IV (Tự luận cho phép học sinh tải ảnh chụp bài giải viết tay để AI Gemini chấm).
> 3. **Khu vực Học tập Tương tác (Gamification)**: Thẻ lật Flashcard công thức Toán 3D, phòng thi đấu trực tiếp kiểu Kahoot bằng mã PIN 6 số, và Bảng xếp hạng học sinh chăm chỉ."

### Prompt 3 — Tạo Công cụ Soạn Bài Tự Học & Nhập 5–10 Bài Tập Cho Từng Dạng (Dùng trong Cursor / Bolt)
> "Hãy viết cho tôi trang Quản trị Nội dung Tự học (`/teacher/self-study-builder`) cho giáo viên Toán. Giáo viên có thể tạo Bài học mới, nhập Lý thuyết bằng Markdown + LaTeX `$ ... $`, thêm không giới hạn các Dạng bài tập (Dạng 1, Dạng 2, Dạng 3...). Ở mỗi Dạng bài tập, giáo viên nhập 'Phương pháp giải' và dán một đoạn văn bản gồm 5 đến 10 câu hỏi Toán (có công thức LaTeX và lời giải), hệ thống tự động tách thành từng câu hỏi, hiển thị Live Preview bằng KaTeX, kiểm tra đủ số lượng từ 5–10 bài mỗi dạng và lưu vào bảng `self_study_lessons` và `lesson_problem_types` trên Supabase."

## 7. Checklist Chuẩn Bị Trước Khi Bắt Đầu Ngay Hôm Nay

- [ ] **Việc 1:** Tạo tài khoản miễn phí tại **Supabase.com** (Database), **Vercel.com** (Hosting) và **Google AI Studio** (`aistudio.google.com` để lấy `GEMINI_API_KEY` miễn phí).
- [ ] **Việc 2:** Vào **SQL Editor** trên Supabase, dán đoạn mã SQL ở **Mục 2** vào và bấm **Run** để tạo sẵn bảng người dùng (có trạng thái duyệt `approval_status`), bảng bài tự học lý thuyết, bảng các dạng bài tập (ràng buộc 5–10 bài/dạng) và chính sách bảo mật chặn học sinh chưa duyệt.
- [ ] **Việc 3:** Bật **Xác minh 2 bước** trên tài khoản Gmail của bạn, vào *Bảo mật -> Mật khẩu ứng dụng (App Passwords)* tạo mật khẩu 16 ký tự để hệ thống tự động gửi thông báo duyệt tài khoản và gửi phiếu bài tập khắc phục lỗi sai về Gmail học sinh đăng ký.
- [ ] **Việc 4:** Mở **Bolt.new** hoặc **v0.dev**, dán **Prompt 1** ở Mục 6 vào để tạo ngay giao diện **Duyệt học sinh** và **Tự học Lý thuyết + Luyện các dạng bài tập (5–10 bài/dạng) + Kiểm tra cuối bài**.
