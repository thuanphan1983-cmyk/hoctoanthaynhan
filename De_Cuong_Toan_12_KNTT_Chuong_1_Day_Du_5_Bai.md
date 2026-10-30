# TỔNG HỢP LÝ THUYẾT TRỌNG TÂM & TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN
## CHƯƠNG I: ỨNG DỤNG ĐẠO HÀM ĐỂ KHẢO SÁT VÀ VẼ ĐỒ THỊ HÀM SỐ
**Môn: Toán 12 — Bộ sách: Kết nối tri thức với cuộc sống (KNTT) | Hệ thống: `hoctoan_ThayNhan`**

---

## BÀI 1: TÍNH ĐƠN ĐIỆU VÀ CỰC TRỊ CỦA HÀM SỐ (6 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 1
#### 1. Tính đơn điệu của hàm số
- **Định nghĩa:** Giả sử hàm số $y = f(x)$ xác định trên $K$ ($K$ là một khoảng, đoạn hoặc nửa khoảng):
  - Hàm số $y = f(x)$ **đồng biến** (tăng) trên $K$ nếu $\forall x_1, x_2 \in K,\ x_1 < x_2 \Rightarrow f(x_1) < f(x_2)$.
  - Hàm số $y = f(x)$ **nghịch biến** (giảm) trên $K$ nếu $\forall x_1, x_2 \in K,\ x_1 < x_2 \Rightarrow f(x_1) > f(x_2)$.
- **Định lý liên hệ giữa dấu đạo hàm và tính đơn điệu:** Cho hàm số $y = f(x)$ có đạo hàm trên khoảng $K$:
  1. Nếu $f'(x) > 0, \forall x \in K$ thì hàm số $f(x)$ **đồng biến** trên khoảng $K$.
  2. Nếu $f'(x) < 0, \forall x \in K$ thì hàm số $f(x)$ **nghịch biến** trên khoảng $K$.
  3. **Định lý mở rộng:** Nếu $f'(x) \ge 0$ (hoặc $f'(x) \le 0$) với mọi $x \in K$ và dấu bằng $f'(x) = 0$ chỉ xảy ra tại một **số hữu hạn điểm** trên khoảng $K$ thì hàm số $f(x)$ vẫn **đồng biến** (hoặc **nghịch biến**) trên khoảng $K$.

#### 2. Cực trị của hàm số
- **Định lý đổi dấu đạo hàm (Quy tắc I):** Giả sử $y = f(x)$ liên tục trên $(a; b)$ chứa $x_0$ và có đạo hàm trên $(a; x_0)$ và $(x_0; b)$:
  - Nếu $f'(x)$ đổi dấu từ **dương ($+$) sang âm ($-$)** khi $x$ đi qua $x_0$ thì $x_0$ là một **điểm cực đại** ($x_{CĐ}$).
  - Nếu $f'(x)$ đổi dấu từ **âm ($-$) sang dương ($+$)** khi $x$ đi qua $x_0$ thì $x_0$ là một **điểm cực tiểu** ($x_{CT}$).
- **Quy tắc II (Đạo hàm cấp hai):** Nếu $f'(x_0) = 0$ và $f''(x_0) < 0 \Rightarrow x_0$ là điểm cực đại; nếu $f'(x_0) = 0$ và $f''(x_0) > 0 \Rightarrow x_0$ là điểm cực tiểu.
- **Phân biệt thuật ngữ:**
  - **Điểm cực đại (cực tiểu) của hàm số:** là hoành độ $x_0$.
  - **Giá trị cực đại (cực tiểu) của hàm số:** là tung độ $y_0 = f(x_0)$ (ký hiệu $y_{CĐ}, y_{CT}$).
  - **Điểm cực đại (cực tiểu) của đồ thị hàm số:** là điểm $M(x_0; f(x_0))$ trên mặt phẳng $Oxy$.

---

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 1 (6 DẠNG)

#### Dạng 1.1: Xét tính đơn điệu và tìm cực trị của hàm số cho bởi công thức tường minh
- **Phương pháp giải (4 bước):**
  1. Tìm tập xác định $D$ của hàm số.
  2. Tính đạo hàm $f'(x)$. Tìm các điểm tới hạn $x_i$ mà tại đó $f'(x) = 0$ hoặc $f'(x)$ không xác định.
  3. Lập bảng biến thiên (xét dấu $f'(x)$).
  4. Kết luận các khoảng đồng biến, nghịch biến (ghi tách từng khoảng bằng từ **"và"**, tuyệt đối không dùng ký hiệu $\cup$) và các điểm cực trị.
- **Ví dụ mẫu:** Tìm các khoảng đơn điệu và cực trị của hàm số $y = \dfrac{x^2 - 2x + 5}{x - 1}$.
  - *Lời giải:* Tập xác định $D = \mathbb{R} \setminus \{1\}$. Đạo hàm $y' = \dfrac{x^2 - 2x - 3}{(x - 1)^2} = 0 \Leftrightarrow x = -1$ hoặc $x = 3$. Lập BBT suy ra hàm số đồng biến trên $(-\infty; -1)$ và $(3; +\infty)$; nghịch biến trên $(-1; 1)$ và $(1; 3)$; đạt cực đại tại $x_{CĐ} = -1, y_{CĐ} = -4$ và đạt cực tiểu tại $x_{CT} = 3, y_{CT} = 4$.

#### Dạng 1.2: Xác định khoảng đơn điệu và cực trị từ Bảng biến thiên, Đồ thị $y = f(x)$ hoặc Đồ thị đạo hàm $y = f'(x)$
- **Phương pháp giải:**
  - **Nếu đề cho BBT hoặc đồ thị của $y = f(x)$:** Khoảng đơn điệu đọc theo trục hoành $Ox$ (từ trái sang phải: nhánh đồ thị đi lên là đồng biến, đi xuống là nghịch biến; đỉnh nhô lên là cực đại, đáy võng xuống là cực tiểu).
  - **Nếu đề cho đồ thị của đạo hàm $y = f'(x)$:** Phần đồ thị $y = f'(x)$ nằm **phía trên trục hoành $Ox$** ứng với $f'(x) > 0$ (hàm đồng biến); nằm **phía dưới trục hoành $Ox$** ứng với $f'(x) < 0$ (hàm nghịch biến). Hoành độ giao điểm nơi đồ thị $f'(x)$ **cắt xuyên qua** trục $Ox$ là điểm cực trị.
- **Ví dụ mẫu:** Cho hàm số $y = f(x)$ xác định trên $\mathbb{R}$ có đồ thị đạo hàm $y = f'(x)$ cắt trục hoành tại $x = -2, x = 1, x = 3$ và $f'(x) < 0$ trên $(-2; 1)$, $f'(x) > 0$ trên $(-\infty; -2) \cup (1; 3) \cup (3; +\infty)$ (tiếp xúc tại $x = 3$). Khi đó hàm số nghịch biến trên $(-2; 1)$, đạt cực đại tại $x = -2$ và đạt cực tiểu tại $x = 1$ ($x = 3$ không đổi dấu nên không là cực trị).

#### Dạng 1.3: Đếm số điểm cực trị từ biểu thức đạo hàm $f'(x)$ (Quy tắc nghiệm bội lẻ)
- **Phương pháp giải:**
  - Nếu $f'(x) = a(x - x_1)^{m_1}(x - x_2)^{m_2}\dots(x - x_k)^{m_k}$ thì $f'(x)$ chỉ đổi dấu khi đi qua các nghiệm có **số mũ $m_i$ lẻ (nghiệm bội lẻ)**.
  - Các nghiệm có **số mũ $m_i$ chẵn (nghiệm bội chẵn)** không làm $f'(x)$ đổi dấu nên **không phải** là điểm cực trị.
- **Ví dụ mẫu:** Cho $f'(x) = x(x - 1)^2(x + 2)^3(x - 4)^4$. Số điểm cực trị của hàm số là $2$ (tại $x = 0$ mũ $1$ và $x = -2$ mũ $3$).

#### Dạng 1.4: Tìm tham số $m$ để hàm số đồng biến hoặc nghịch biến trên tập xác định hoặc trên khoảng $(a; b)$ cho trước
- **Phương pháp giải:**
  1. **Hàm bậc ba $y = ax^3 + bx^2 + cx + d$ ($a \ne 0$) đơn điệu trên $\mathbb{R}$:**
     - Đồng biến trên $\mathbb{R} \Leftrightarrow y' = 3ax^2 + 2bx + c \ge 0, \forall x \in \mathbb{R} \Leftrightarrow \begin{cases} a > 0 \\ \Delta'_{y'} = b^2 - 3ac \le 0 \end{cases}$.
     - Nghịch biến trên $\mathbb{R} \Leftrightarrow y' \le 0, \forall x \in \mathbb{R} \Leftrightarrow \begin{cases} a < 0 \\ \Delta'_{y'} = b^2 - 3ac \le 0 \end{cases}$.
  2. **Hàm phân thức $y = \dfrac{ax + b}{cx + d}$ đơn điệu trên từng khoảng xác định và trên khoảng $(a; b)$:**
     - Trên từng khoảng xác định: Đồng biến $\Leftrightarrow ad - bc > 0$; Nghịch biến $\Leftrightarrow ad - bc < 0$ (**không lấy dấu bằng**).
     - Trên khoảng $(\alpha; \beta)$: Thêm điều kiện nghiệm mẫu số $x_0 = -\dfrac{d}{c} \notin (\alpha; \beta)$.
  3. **Phương pháp cô lập tham số $m$ trên khoảng $(a; b)$:**
     - Đưa bất phương trình $y' \ge 0, \forall x \in (a; b)$ về dạng $m \ge g(x), \forall x \in (a; b) \Leftrightarrow m \ge \max_{[a; b]} g(x)$ (hoặc $m \le g(x) \Leftrightarrow m \le \min_{[a; b]} g(x)$).
- **Ví dụ mẫu:** Tìm số giá trị nguyên của $m$ để hàm số $y = \dfrac{mx - 4}{x - m}$ đồng biến trên $(0; +\infty)$.
  - *Lời giải:* Điều kiện: $\begin{cases} y' = \dfrac{-m^2 + 4}{(x - m)^2} > 0 \\ m \notin (0; +\infty) \end{cases} \Leftrightarrow \begin{cases} -2 < m < 2 \\ m \le 0 \end{cases} \Leftrightarrow -2 < m \le 0$. Vì $m \in \mathbb{Z} \Rightarrow m \in \{-1; 0\}$ (có $2$ giá trị).

#### Dạng 1.5: Tìm tham số $m$ để hàm số có cực trị, đạt cực trị tại $x = x_0$ hoặc thỏa mãn hệ thức Vi-ét giữa hai điểm cực trị $x_1, x_2$
- **Phương pháp giải:**
  1. **Hàm bậc ba có 2 điểm cực trị:** $y' = 3ax^2 + 2bx + c = 0$ có 2 nghiệm phân biệt $\Leftrightarrow \begin{cases} a \ne 0 \\ \Delta'_{y'} = b^2 - 3ac > 0 \end{cases}$.
  2. **Đạt cực đại / cực tiểu tại $x = x_0$:** Giải hệ $\begin{cases} f'(x_0) = 0 \\ f''(x_0) < 0 \text{ (nếu CĐ) hoặc } f''(x_0) > 0 \text{ (nếu CT)} \end{cases}$ (hoặc giải $f'(x_0) = 0$ tìm $m$ rồi thử lại bằng BBT).
  3. **Thỏa mãn hệ thức đối xứng giữa hai điểm cực trị $x_1, x_2$:** Dùng định lý Vi-ét cho phương trình $y' = 0$: $x_1 + x_2 = -\dfrac{2b}{3a}$ và $x_1 x_2 = \dfrac{c}{3a}$.
  4. **Phương trình đường thẳng đi qua 2 điểm cực trị của hàm bậc ba:** Chia đa thức $y$ cho $y'$ được $y = Q(x)\cdot y' + R(x) \Rightarrow$ đường thẳng qua 2 cực trị là $y = R(x) = \left(c - \dfrac{b^2}{3a}\right)x + d - \dfrac{bc}{9a}$.
- **Ví dụ mẫu:** Tìm $m$ để hàm số $y = \dfrac{1}{3}x^3 - mx^2 + (m^2 - 4)x + 1$ đạt cực đại tại $x = 1$.
  - *Lời giải:* $y' = x^2 - 2mx + m^2 - 4;\ y'' = 2x - 2m$. Để đạt cực đại tại $x = 1$: $\begin{cases} y'(1) = 1 - 2m + m^2 - 4 = 0 \\ y''(1) = 2 - 2m < 0 \end{cases} \Leftrightarrow \begin{cases} m = 3 \text{ hoặc } m = -1 \\ m > 1 \end{cases} \Rightarrow m = 3$.

#### Dạng 1.6: Xét tính đơn điệu và tìm cực trị của hàm số hợp $g(x) = f(u(x))$
- **Phương pháp giải:**
  - Tính đạo hàm hàm hợp: $g'(x) = u'(x) \cdot f'(u(x))$.
  - Giải phương trình $g'(x) = 0 \Leftrightarrow \begin{bmatrix} u'(x) = 0 \\ f'(u(x)) = 0 \Leftrightarrow u(x) = a_i \text{ (với } a_i \text{ là nghiệm bội lẻ của } f'(t) = 0\text{)} \end{bmatrix}$.
  - Xét dấu $g'(x)$ trên trục số hoặc đếm tổng số nghiệm bội lẻ để suy ra khoảng đơn điệu và số điểm cực trị.
- **Ví dụ mẫu:** Cho $f'(x) = x(x - 2)$. Tìm số điểm cực trị của $g(x) = f(x^2)$.
  - *Lời giải:* $g'(x) = 2x \cdot f'(x^2) = 2x \cdot x^2(x^2 - 2) = 2x^3(x - \sqrt{2})(x + \sqrt{2}) = 0 \Leftrightarrow x \in \{0; \sqrt{2}; -\sqrt{2}\}$ (cả 3 nghiệm đều bội lẻ) $\Rightarrow$ có $3$ điểm cực trị.

---

## BÀI 2: GIÁ TRỊ LỚN NHẤT VÀ GIÁ TRỊ NHỎ NHẤT CỦA HÀM SỐ (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 2
- **Định nghĩa:** Cho hàm số $y = f(x)$ xác định trên tập $D$:
  - $M = \max_{D} f(x) \Leftrightarrow \begin{cases} f(x) \le M, \forall x \in D \\ \exists x_0 \in D: f(x_0) = M \end{cases}$
  - $m = \min_{D} f(x) \Leftrightarrow \begin{cases} f(x) \ge m, \forall x \in D \\ \exists x_0 \in D: f(x_0) = m \end{cases}$
- **Định lý:** Mọi hàm số liên tục trên một đoạn $[a; b]$ đều đạt được giá trị lớn nhất và giá trị nhỏ nhất trên đoạn đó.

---

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 2 (5 DẠNG)

#### Dạng 2.1: Tìm GTLN và GTNN của hàm số liên tục trên một đoạn $[a; b]$ (Quy tắc 3 bước)
- **Phương pháp giải:**
  1. Tìm các điểm $x_1, x_2, \dots, x_n \in (a; b)$ mà tại đó $f'(x) = 0$ hoặc $f'(x)$ không tồn tại (chú ý loại nghiệm ngoài khoảng $(a; b)$).
  2. Tính $f(a), f(x_1), \dots, f(x_n), f(b)$.
  3. Số lớn nhất là $\max_{[a; b]} f(x)$ và số nhỏ nhất là $\min_{[a; b]} f(x)$.
  - *Đặc biệt:* Nếu $f(x)$ luôn đồng biến (hoặc luôn nghịch biến) trên $[a; b]$ thì GTLN và GTNN đạt tại hai đầu mút $f(a), f(b)$.
- **Ví dụ mẫu:** Tìm GTLN, GTNN của $f(x) = x^3 - 3x^2 - 9x + 35$ trên đoạn $[-4; 4]$.
  - *Lời giải:* $f'(x) = 3x^2 - 6x - 9 = 0 \Leftrightarrow x = -1 \in (-4; 4)$ hoặc $x = 3 \in (-4; 4)$. Ta có $f(-4) = -41,\ f(-1) = 40,\ f(3) = 8,\ f(4) = 15 \Rightarrow \max_{[-4; 4]} f(x) = 40$ và $\min_{[-4; 4]} f(x) = -41$.

#### Dạng 2.2: Tìm GTLN và GTNN của hàm số trên một khoảng mở $(a; b)$ hoặc nửa khoảng
- **Phương pháp giải:**
  - Bắt buộc lập **Bảng biến thiên** của hàm số trên khoảng $(a; b)$.
  - Nếu trên $(a; b)$ hàm số liên tục và có **duy nhất một điểm cực trị** $x_0$: nếu $x_0$ là điểm cực tiểu thì $\min_{(a; b)} f(x) = f(x_0)$; nếu $x_0$ là điểm cực đại thì $\max_{(a; b)} f(x) = f(x_0)$.
  - *Mẹo giải nhanh bằng BĐT Cauchy (AM-GM):* Với hàm $f(x) = ax + \dfrac{b}{x - c}$ ($a, b > 0$) trên khoảng $(c; +\infty)$, viết $f(x) = a(x - c) + \dfrac{b}{x - c} + ac \ge 2\sqrt{ab} + ac$.
- **Ví dụ mẫu:** Tìm GTNN của $f(x) = x + \dfrac{9}{x - 2}$ trên khoảng $(2; +\infty)$.
  - *Lời giải:* Với $x > 2$, $f'(x) = 1 - \dfrac{9}{(x - 2)^2} = 0 \Leftrightarrow x = 5 \in (2; +\infty)$. Lập BBT suy ra $\min_{(2; +\infty)} f(x) = f(5) = 8$.

#### Dạng 2.3: Đọc GTLN và GTNN của hàm số từ Bảng biến thiên hoặc Đồ thị cho trước
- **Phương pháp giải:**
  - Giới hạn phần đồ thị hoặc BBT chỉ trong phạm vi tập $D$ mà đề bài yêu cầu (ví dụ cắt đoạn $[a; b]$).
  - Điểm cao nhất (có tồn tại dấu $"="$ trên đồ thị) có tung độ là GTLN $M$; điểm thấp nhất có tung độ là GTNN $m$. Chú ý: tại đầu mút ngoặc tròn $(a; b)$ hoặc nơi có giới hạn $\pm\infty$, hàm số không đạt giá trị tại đó.
- **Ví dụ mẫu:** Nếu trên đoạn $[-1; 3]$ đồ thị hàm số có điểm cao nhất là $(-1; 4)$ và điểm thấp nhất là $(2; -2)$ thì $\max_{[-1; 3]} f(x) = 4$ và $\min_{[-1; 3]} f(x) = -2$.

#### Dạng 2.4: Tìm GTLN và GTNN bằng phương pháp đặt ẩn phụ $t = u(x)$ (Hàm hợp, lượng giác, căn thức, mũ – logarit)
- **Phương pháp giải:**
  1. Đặt $t = u(x)$ với $x \in D$, tìm tập giá trị $T = [t_{\min}; t_{\max}]$ của ẩn phụ $t$.
  2. Chuyển bài toán về khảo sát hàm số $g(t)$ trên đoạn $T = [t_{\min}; t_{\max}]$.
- **Ví dụ mẫu:** Tìm GTLN của hàm số $y = \sin^3 x - 3\sin x + 2$.
  - *Lời giải:* Đặt $t = \sin x \in [-1; 1]$. Xét hàm $g(t) = t^3 - 3t + 2$ trên đoạn $[-1; 1]$ có $g'(t) = 3t^2 - 3 \le 0, \forall t \in [-1; 1] \Rightarrow \max_{[-1; 1]} g(t) = g(-1) = 4$ và $\min_{[-1; 1]} g(t) = g(1) = 0$.

#### Dạng 2.5: Tìm tham số $m$ để GTLN, GTNN của hàm số trên đoạn $[a; b]$ thỏa mãn điều kiện cho trước
- **Phương pháp giải:**
  - **Loại 1 — Hàm bậc ba $y = f(x) + m$ trên $[a; b]$:** Tìm $\max_{[a; b]} f(x) = A$ và $\min_{[a; b]} f(x) = B$. Khi đó $\max_{[a; b]} y = A + m$ và $\min_{[a; b]} y = B + m$, thay vào điều kiện đề bài để giải tìm $m$.
  - **Loại 2 — Hàm phân thức $y = \dfrac{ax + b}{cx + d}$ trên đoạn $[\alpha; \beta]$:** Vì hàm đơn điệu trên $[\alpha; \beta]$ (với điều kiện $-\dfrac{d}{c} \notin [\alpha; \beta]$) nên hai giá trị lớn nhất và nhỏ nhất chắc chắn là hai đầu mút $y(\alpha)$ và $y(\beta)$.
- **Ví dụ mẫu:** Tìm $m$ để hàm số $y = \dfrac{x + m}{x - 1}$ thỏa mãn $\min_{[2; 4]} y = 3$.
  - *Lời giải:* Trên $[2; 4]$, $y(2) = m + 2$ và $y(4) = \dfrac{m + 4}{3}$. Xét $y(4) = 3 \Leftrightarrow m = 5$, khi đó $y(2) = 7 > 3$ (thỏa mãn).

---

## BÀI 3: ĐƯỜNG TIỆM CẬN CỦA ĐỒ THỊ HÀM SỐ (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 3
1. **Tiệm cận ngang (TCN):** Đường thẳng $y = y_0$ là TCN nếu $\lim_{x \to +\infty} f(x) = y_0$ hoặc $\lim_{x \to -\infty} f(x) = y_0$ (tối đa $2$ TCN).
2. **Tiệm cận đứng (TCĐ):** Đường thẳng $x = x_0$ là TCĐ nếu ít nhất một trong các giới hạn $\lim_{x \to x_0^+} f(x),\ \lim_{x \to x_0^-} f(x)$ bằng $+\infty$ hoặc $-\infty$.
3. **Tiệm cận xiên (TCX):** Đường thẳng $y = ax + b$ ($a \ne 0$) là TCX nếu $\lim_{x \to +\infty} [f(x) - (ax + b)] = 0$ hoặc $\lim_{x \to -\infty} [f(x) - (ax + b)] = 0$.

---

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 3 (5 DẠNG)

#### Dạng 3.1: Tìm TCN, TCĐ, TCX của đồ thị hàm số cho bởi công thức
- **Phương pháp giải:**
  - **Hàm bậc nhất trên bậc nhất $y = \dfrac{ax + b}{cx + d}$ ($c \ne 0, ad - bc \ne 0$):** TCĐ là $x = -\dfrac{d}{c}$; TCN là $y = \dfrac{a}{c}$ (không có TCX).
  - **Hàm bậc hai trên bậc nhất $y = \dfrac{ax^2 + bx + c}{mx + n}$ ($a, m \ne 0$, tử không chia hết cho mẫu):** Chia đa thức tử cho mẫu được $y = px + q + \dfrac{r}{mx + n}$ ($r \ne 0$) $\Rightarrow$ TCĐ là $x = -\dfrac{n}{m}$ và TCX là $y = px + q$ (không có TCN).
  - **Hàm phân thức hữu tỉ tổng quát $y = \dfrac{P(x)}{Q(x)}$:** Nếu $\deg P < \deg Q \Rightarrow$ TCN $y = 0$; nếu $\deg P = \deg Q \Rightarrow$ TCN $y = \dfrac{a_n}{b_n}$; nếu $\deg P = \deg Q + 1 \Rightarrow$ chia đa thức để tìm TCX.
- **Ví dụ mẫu:** Đồ thị hàm số $y = \dfrac{2x^2 - 3x - 1}{x - 2} = 2x + 1 + \dfrac{1}{x - 2}$ có TCĐ là $x = 2$ và TCX là $y = 2x + 1$.

#### Dạng 3.2: Đọc và đếm số đường tiệm cận từ Bảng biến thiên hoặc Đồ thị hàm số
- **Phương pháp giải:**
  - **Tìm TCN trên BBT:** Nhìn tại hai cột $x \to -\infty$ và $x \to +\infty$. Nếu dòng $y$ xuất hiện **số thực hữu hạn $y_0$** thì $y = y_0$ là TCN.
  - **Tìm TCĐ trên BBT:** Nhìn tại các cột điểm gián đoạn $x = x_0$ (thường có gạch sọc đôi `||`). Nếu bên trái hoặc bên phải $x_0$ ở dòng $y$ xuất hiện $+\infty$ hoặc $-\infty$ thì $x = x_0$ là TCĐ.
- **Ví dụ mẫu:** Nếu BBT có $\lim_{x \to -\infty} y = 1,\ \lim_{x \to +\infty} y = 3$ và $\lim_{x \to 2^-} y = -\infty$ thì đồ thị có $2$ TCN ($y = 1, y = 3$) và $1$ TCĐ ($x = 2$).

#### Dạng 3.3: Biện luận số đường tiệm cận đứng khi tử số và mẫu số có nghiệm chung (Dạng $\dfrac{0}{0}$)
- **Phương pháp giải:**
  - Giải phương trình mẫu số $Q(x) = 0$ tìm các nghiệm $x_0$.
  - Nếu $P(x_0) \ne 0$: chắc chắn $x = x_0$ là TCĐ.
  - Nếu $P(x_0) = 0$: phân tích tử và mẫu thành nhân tử để rút gọn $(x - x_0)$. Sau khi rút gọn tối giản, nếu ở mẫu **vẫn còn** nhân tử $(x - x_0)$ (hoặc $\sqrt{x - x_0}$) thì $x = x_0$ vẫn là TCĐ; nếu mẫu mất hoàn toàn $(x - x_0)$ thì $x = x_0$ **không** phải là TCĐ.
- **Ví dụ mẫu:** Tìm số TCĐ của $y = \dfrac{x - 2}{x^2 - 3x + 2}$.
  - *Lời giải:* Rút gọn $y = \dfrac{x - 2}{(x - 1)(x - 2)} = \dfrac{1}{x - 1}$ ($x \ne 2$). Vậy nghiệm $x = 2$ bị triệt tiêu, đồ thị chỉ có đúng $1$ TCĐ là $x = 1$.

#### Dạng 3.4: Các bài toán hình học liên quan đến đường tiệm cận (Giao điểm, diện tích, khoảng cách)
- **Phương pháp giải:**
  - **Tâm đối xứng $I$:** Là giao điểm của hai đường tiệm cận (TCĐ $\cap$ TCN hoặc TCĐ $\cap$ TCX).
  - **Hình chữ nhật tạo bởi 2 tiệm cận của $y = \dfrac{ax + b}{cx + d}$ và 2 trục tọa độ:** Có hai kích thước là $\left|-\dfrac{d}{c}\right|$ và $\left|\dfrac{a}{c}\right|$, suy ra diện tích $S = \left|\dfrac{ad}{c^2}\right|$ và chu vi $C = 2\left(\left|\dfrac{d}{c}\right| + \left|\dfrac{a}{c}\right|\right)$.
  - **Tam giác tạo bởi TCĐ, TCX và một trục tọa độ:** Tìm tọa độ 3 đỉnh là giao điểm từng đôi một rồi tính diện tích.
- **Ví dụ mẫu:** Hai đường tiệm cận của $y = \dfrac{2x + 1}{x - 3}$ là $x = 3$ và $y = 2$, tạo với hai trục $Ox, Oy$ hình chữ nhật có diện tích $S = 3 \times 2 = 6$.

#### Dạng 3.5: Tìm tham số $m$ để đồ thị hàm số có đường tiệm cận thỏa mãn điều kiện cho trước
- **Phương pháp giải:**
  - Để $y = \dfrac{P(x)}{x - m}$ có TCĐ $x = m$: điều kiện là nghiệm $x = m$ không làm tử số bằng $0$, tức $P(m) \ne 0$.
  - Để đồ thị $y = \dfrac{x - a}{x^2 - 2x + m}$ có đúng $2$ TCĐ: phương trình mẫu $x^2 - 2x + m = 0$ phải có $2$ nghiệm phân biệt đều khác $a$.
- **Ví dụ mẫu:** Tìm $m$ để đồ thị $y = \dfrac{2x + 3}{x - m}$ có tiệm cận đứng đi qua điểm $A(5; 2)$.
  - *Lời giải:* TCĐ là $x = m$ (với $2m + 3 \ne 0 \Leftrightarrow m \ne -\dfrac{3}{2}$). Vì TCĐ đi qua $A(5; 2)$ nên $m = 5$ (thỏa mãn).

---

## BÀI 4: KHẢO SÁT SỰ BIẾN THIÊN VÀ VẼ ĐỒ THỊ CỦA HÀM SỐ (6 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 4
- **Quy trình 3 bước khảo sát và vẽ đồ thị hàm số chuẩn SGK KNTT:**
  1. **Bước 1:** Tìm tập xác định của hàm số.
  2. **Bước 2 (Khảo sát sự biến thiên):** Tính đạo hàm $y'$, xét dấu $y'$, tìm khoảng đơn điệu và cực trị; tìm giới hạn tại vô cực, giới hạn vô cực và các đường tiệm cận (nếu có); lập **Bảng biến thiên**.
  3. **Bước 3 (Vẽ đồ thị):** Xác định các điểm cực trị, giao điểm với trục tung ($x = 0$), trục hoành ($y = 0$), tâm đối xứng $I$ và vẽ đồ thị.

---

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 4 (6 DẠNG)

#### Dạng 4.1: Khảo sát sự biến thiên và vẽ đồ thị 3 loại hàm số chuẩn Chương trình Toán 12 KNTT
- **Phương pháp giải:**
  1. **Hàm số bậc ba $y = ax^3 + bx^2 + cx + d$ ($a \ne 0$):** TXĐ $D = \mathbb{R}$; không có tiệm cận; có 2 cực trị khi $b^2 - 3ac > 0$, không có cực trị khi $b^2 - 3ac \le 0$; tâm đối xứng là điểm uốn $I(x_0; y_0)$ với $x_0 = -\dfrac{b}{3a}$.
  2. **Hàm phân thức bậc nhất/bậc nhất $y = \dfrac{ax + b}{cx + d}$ ($c \ne 0, ad - bc \ne 0$):** TXĐ $D = \mathbb{R} \setminus \left\{-\dfrac{d}{c}\right\}$; luôn đơn điệu trên từng khoảng xác định, không có cực trị; TCĐ $x = -\dfrac{d}{c}$, TCN $y = \dfrac{a}{c}$; tâm đối xứng $I\left(-\dfrac{d}{c}; \dfrac{a}{c}\right)$.
  3. **Hàm phân thức bậc hai/bậc nhất $y = \dfrac{ax^2 + bx + c}{mx + n} = px + q + \dfrac{r}{mx + n}$ ($a, m, r \ne 0$):** TXĐ $D = \mathbb{R} \setminus \left\{-\dfrac{n}{m}\right\}$; TCĐ $x = -\dfrac{n}{m}$, TCX $y = px + q$; tâm đối xứng là giao điểm của TCĐ và TCX.

#### Dạng 4.2: Nhận diện đồ thị và xác định công thức hàm số từ đường cong hoặc Bảng biến thiên
- **Phương pháp giải (Loại trừ nhanh 4 bước):**
  1. Nhìn hình dáng đồ thị để nhận diện loại hàm (chữ $N$ hoặc suy biến là hàm bậc ba; 2 nhánh có TCĐ & TCN là hàm bậc 1/1; 2 nhánh có TCĐ & TCX là hàm bậc 2/1).
  2. Nhìn nhánh ngoài cùng bên phải (hoặc tiệm cận) để xác định dấu hệ số đứng đầu.
  3. Thay tọa độ giao điểm với trục tung $(0; y_0)$, trục hoành và các điểm cực trị $(x_{CĐ}; y_{CĐ}), (x_{CT}; y_{CT})$.
- **Ví dụ mẫu:** Đường cong đi qua $(0; 2)$, đạt cực đại tại $(-1; 4)$ và đạt cực tiểu tại $(1; 0)$ có $y' = 0$ tại $x = \pm 1$ và nhánh phải đi lên ($a > 0$) nên là đồ thị hàm số $y = x^3 - 3x + 2$.

#### Dạng 4.3: Xét dấu các hệ số $a, b, c, d$ từ đồ thị hàm số
- **Phương pháp giải:**
  1. **Với hàm bậc ba $y = ax^3 + bx^2 + cx + d$:**
     - **Dấu của $a$:** Nhánh ngoài cùng bên phải đi lên $\Rightarrow a > 0$; đi xuống $\Rightarrow a < 0$.
     - **Dấu của $d$:** Giao với trục tung $Oy$ tại $(0; d)$ nằm trên $Ox \Rightarrow d > 0$; nằm dưới $Ox \Rightarrow d < 0$; đi qua $O(0; 0) \Rightarrow d = 0$.
     - **Dấu của $c$:** Tích hai điểm cực trị $x_1 x_2 = \dfrac{c}{3a}$ ($x_1, x_2$ trái dấu $\Rightarrow a, c$ trái dấu; một cực trị có $x = 0 \Rightarrow c = 0$).
     - **Dấu của $b$:** Tổng hai điểm cực trị $x_1 + x_2 = -\dfrac{2b}{3a}$ hoặc hoành độ tâm đối xứng $x_I = -\dfrac{b}{3a}$.
  2. **Với hàm phân thức $y = \dfrac{ax + b}{cx + d}$:**
     - TCĐ $x = -\dfrac{d}{c}$, TCN $y = \dfrac{a}{c}$, giao $Oy$ tại $\left(0; \dfrac{b}{d}\right)$, giao $Ox$ tại $\left(-\dfrac{b}{a}; 0\right)$.

#### Dạng 4.4: Tìm tâm đối xứng, trục đối xứng và cặp điểm đối xứng trên đồ thị
- **Phương pháp giải:**
  - **Tâm đối xứng hàm bậc ba:** Giải $y'' = 6ax + 2b = 0 \Leftrightarrow x_I = -\dfrac{b}{3a} \Rightarrow I(x_I; y(x_I))$ (cũng là trung điểm đoạn nối 2 điểm cực trị).
  - **Tâm đối xứng hàm phân thức:** Giao điểm $I$ của hai đường tiệm cận.
  - **Hai trục đối xứng của đồ thị $y = \dfrac{ax + b}{cx + d}$:** Là hai đường phân giác của góc tạo bởi TCĐ và TCN: $y - \dfrac{a}{c} = \pm\left(x + \dfrac{d}{c}\right)$.

#### Dạng 4.5: Bài toán tương giao hai đồ thị — Biện luận số nghiệm của phương trình bằng đồ thị
- **Phương pháp giải:**
  - Số giao điểm của hai đồ thị $y = f(x)$ và $y = g(x)$ bằng số nghiệm thực phân biệt của phương trình hoành độ giao điểm $f(x) = g(x)$.
  - **Phương pháp cô lập tham số $m$:** Đưa phương trình về dạng $f(x) = h(m)$, kẻ đường thẳng nằm ngang $y = h(m)$ cắt qua BBT hoặc đồ thị của $y = f(x)$ để đếm số giao điểm.
- **Ví dụ mẫu:** Phương trình $x^3 - 3x^2 + 2 = m$ có $3$ nghiệm thực phân biệt khi và chỉ khi $y_{CT} < m < y_{CĐ} \Leftrightarrow -2 < m < 2$.

#### Dạng 4.6: Phương trình tiếp tuyến của đồ thị hàm số & Đồ thị hàm chứa dấu giá trị tuyệt đối
- **Phương pháp giải:**
  - **Phương trình tiếp tuyến của $(C): y = f(x)$ tại điểm $M(x_0; y_0) \in (C)$:**
    $$y = f'(x_0)(x - x_0) + f(x_0)$$
    Trong đó $k = f'(x_0)$ là hệ số góc của tiếp tuyến (nếu tiếp tuyến song song với $y = ax + b$ thì $f'(x_0) = a$; nếu vuông góc thì $f'(x_0) \cdot a = -1$).
  - **Suy đồ thị chứa giá trị tuyệt đối:**
    - Đồ thị $y = |f(x)|$: Giữ nguyên phần đồ thị $(C)$ nằm phía trên $Ox$, lấy đối xứng phần nằm dưới $Ox$ qua trục $Ox$. Số điểm cực trị của $y = |f(x)|$ bằng tổng số điểm cực trị của $f(x)$ cộng với số nghiệm bội lẻ của phương trình $f(x) = 0$.

---

## BÀI 5: ỨNG DỤNG ĐẠO HÀM ĐỂ GIẢI QUYẾT MỘT SỐ VẤN ĐỀ LIÊN QUAN ĐẾN THỰC TIỄN (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 5
- **Ý nghĩa thực tiễn của đạo hàm:** Đạo hàm $f'(x_0)$ là **tốc độ thay đổi tức thời** của đại lượng $y = f(x)$ theo đại lượng $x$ tại điểm $x = x_0$.
- **Quy trình 4 bước giải bài toán tối ưu hóa thực tiễn:**
  1. **Mô hình hóa toán học:** Chọn ẩn $x$, đặt điều kiện thực tế cho $x$ và lập hàm mục tiêu $y = f(x)$.
  2. **Tính đạo hàm:** Tính $f'(x)$ và giải phương trình $f'(x) = 0$.
  3. **Tìm GTLN / GTNN:** Lập bảng biến thiên hoặc so sánh giá trị trên đoạn để tìm $\max f(x)$ hoặc $\min f(x)$.
  4. **Kết luận thực tiễn:** Kiểm tra điều kiện, làm tròn số theo yêu cầu và trả lời bài toán.

---

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 5 (5 DẠNG)

#### Dạng 5.1: Bài toán tốc độ thay đổi tức thời trong Vật lý & Kỹ thuật (Chuyển động, Điện học)
- **Phương pháp giải:**
  - Phương trình quãng đường $s = s(t) \Rightarrow$ **Vận tốc tức thời** $v(t) = s'(t)$ và **Gia tốc tức thời** $a(t) = v'(t) = s''(t)$.
  - Vật dừng lại khi $v(t) = 0$; vận tốc đạt lớn nhất khi $v'(t) = a(t) = 0$ (hoặc tại đỉnh parabol nếu $v(t)$ là hàm bậc hai có hệ số $a < 0$).
  - Điện lượng $q = q(t) \Rightarrow$ **Cường độ dòng điện tức thời** $I(t) = q'(t)$.
- **Ví dụ mẫu:** Chất điểm chuyển động theo $s(t) = -t^3 + 6t^2 + 9t$ ($t \in [0; 4]$) có $v(t) = s'(t) = -3t^2 + 12t + 9 = -3(t - 2)^2 + 21 \le 21\text{ m/s}$, đạt vận tốc lớn nhất $21\text{ m/s}$ tại $t = 2\text{ s}$.

#### Dạng 5.2: Bài toán tốc độ thay đổi và cực trị trong Sinh học, Y học, Hóa học & Môi trường
- **Phương pháp giải:**
  - Số lượng cá thể quần thể $N(t) \Rightarrow$ tốc độ tăng trưởng tức thời tại thời điểm $t$ là $N'(t)$.
  - Nồng độ thuốc trong máu bệnh nhân $C(t)$ (với $t \ge 0$) đạt giá trị lớn nhất tại nghiệm dương của phương trình $C'(t) = 0$ (nơi $C'(t)$ đổi dấu từ $+$ sang $-$).
- **Ví dụ mẫu:** Nồng độ thuốc $C(t) = \dfrac{2t}{t^2 + 4}$ ($t \ge 0$) có $C'(t) = \dfrac{8 - 2t^2}{(t^2 + 4)^2} = 0 \Leftrightarrow t = 2$ giờ, khi đó $C_{\max} = C(2) = 0{,}5\text{ mg/lít}$.

#### Dạng 5.3: Bài toán tối ưu hóa Hình học phẳng & Hình học không gian (Thể tích, diện tích, chi phí vật liệu)
- **Phương pháp giải & Công thức giải nhanh các mô hình kinh điển:**
  1. **Cắt 4 góc hình vuông cạnh $x$ từ tấm tôn vuông cạnh $a$ để gấp thành hộp không nắp:**
     - Điều kiện $0 < x < \dfrac{a}{2}$; thể tích $V(x) = x(a - 2x)^2$ đạt lớn nhất khi $x = \dfrac{a}{6}$ với $V_{\max} = \dfrac{2a^3}{27}$.
  2. **Xây bể chứa nước không nắp hình hộp chữ nhật đáy vuông cạnh $x$, thể tích $V$ cho trước:**
     - Chiều cao $h = \dfrac{V}{x^2}$; tổng diện tích cần xây $S(x) = x^2 + 4xh = x^2 + \dfrac{4V}{x}$ đạt nhỏ nhất khi $S'(x) = 2x - \dfrac{4V}{x^2} = 0 \Leftrightarrow x = \sqrt[3]{2V}$ (khi đó $x = 2h$).
  3. **Thiết kế vỏ lon hình trụ có thể tích $V$ cho trước tốn ít vật liệu nhất:**
     - Nếu hình trụ kín 2 đáy: $S_{tp} = 2\pi R^2 + \dfrac{2V}{R}$ nhỏ nhất khi chiều cao bằng đường kính đáy ($h = 2R$).
     - Nếu hình trụ không nắp trên: $S = \pi R^2 + \dfrac{2V}{R}$ nhỏ nhất khi chiều cao bằng bán kính đáy ($h = R$).

#### Dạng 5.4: Bài toán tối ưu hóa Đường đi – Thời gian – Chi phí trên hai môi trường (Bờ biển & Dưới nước)
- **Phương pháp giải:**
  - Giả sử điểm xuất phát $A$ cách bờ thẳng $BC$ một đoạn vuông góc $AB = d$, khoảng cách dọc bờ $BC = L$. Vận tốc (hoặc đơn giá chi phí) dưới nước là $v_1$, trên bờ là $v_2$.
  - Gọi $x = BM$ ($0 \le x \le L$) là khoảng cách từ chân đường vuông góc $B$ đến điểm cập bờ $M$. Khi đó quãng đường dưới nước là $AM = \sqrt{d^2 + x^2}$ và quãng đường trên bờ là $MC = L - x$.
  - Lập hàm tổng thời gian $T(x) = \dfrac{\sqrt{d^2 + x^2}}{v_1} + \dfrac{L - x}{v_2}$ (hoặc hàm tổng chi phí $C(x) = c_1\sqrt{d^2 + x^2} + c_2(L - x)$) rồi giải $T'(x) = 0$.

#### Dạng 5.5: Bài toán tối ưu hóa trong Kinh tế (Chi phí, Doanh thu, Lợi nhuận & Điều chỉnh giá bán)
- **Phương pháp giải:**
  1. **Bài toán hàm Chi phí – Doanh thu – Lợi nhuận theo sản lượng $x$:**
     - Tổng lợi nhuận $P(x) = R(x) - C(x)$ đạt lớn nhất khi $P'(x) = 0 \Leftrightarrow R'(x) = C'(x)$ (doanh thu biên bằng chi phí biên).
     - Chi phí trung bình mỗi sản phẩm $\overline{C}(x) = \dfrac{C(x)}{x}$ đạt nhỏ nhất khi $\overline{C}'(x) = 0$.
  2. **Bài toán điều chỉnh giá bán / giá thuê phòng:**
     - Gọi $x$ là số lần giảm (hoặc tăng) giá bán, mỗi lần điều chỉnh một lượng $\Delta p$.
     - Biểu diễn giá bán mới $p(x) = p_0 \mp x \cdot \Delta p$ và sản lượng tiêu thụ mới $q(x) = q_0 \pm x \cdot \Delta q$.
     - Lập hàm doanh thu $R(x) = p(x) \cdot q(x)$ hoặc hàm lợi nhuận $P(x) = [p(x) - c_{\text{vốn}}] \cdot q(x)$ rồi tìm cực đại của hàm bậc hai.
- **Ví dụ mẫu:** Bán giá $200$ nghìn đồng thì bán được $100$ áo/tuần; cứ giảm $10$ nghìn đồng ($x$ lần) thì bán thêm được $10x$ áo. Hàm doanh thu $R(x) = (200 - 10x)(100 + 10x) = -100x^2 + 1000x + 20000$ đạt GTLN khi $x = 5$ (tức giá bán tối ưu là $150$ nghìn đồng/chiếc).

---

## HỆ THỐNG 50 BÀI TẬP TỰ LUẬN TỰ LUYỆN CÓ LỜI GIẢI CHI TIẾT THEO CƠ CẤU 4 BIẾT – 3 HIỂU – 3 VẬN DỤNG (10 BÀI / DẠNG)
> **Cơ cấu phân tầng chuẩn sư phạm (10 bài tự luận mỗi dạng toán):**
> - **4 bài Mức độ 1 (Nhận biết):** Nhận diện kiến thức cốt lõi, công thức nền tảng, tập xác định, tính đạo hàm cơ bản, đọc đồ thị / BBT.
> - **3 bài Mức độ 2 (Thông hiểu):** Áp dụng quy tắc tính đạo hàm thương/căn, giải phương trình, lập bảng biến thiên, tính GTLN-GTNN, tìm tiệm cận, viết PTTT.
> - **3 bài Mức độ 3 (Vận dụng):** Biện luận tham số $m$, tìm cực trị thỏa mãn điều kiện hình học/đại số, tối ưu hóa mô hình thực tiễn liên môn.

---
### 1. Dạng 1 (SGK Toán 12 KNTT): Tính đơn điệu và cực trị của hàm số — 10 Bài tự luận phân tầng
#### Bài 1.1 [Mức 1: Nhận biết]
- **Đề bài:** Xét tính đơn điệu và tìm các khoảng đồng biến, nghịch biến của hàm số bậc ba $y = x^3 - 3x^2 + 2$.
- **Phương pháp & Gợi ý giải:** Tìm tập xác định, tính đạo hàm bậc nhất $y'$, giải phương trình $y' = 0$ và lập bảng xét dấu $y'$.
- **Lời giải chi tiết từng bước:**
- **Bước 1 (TXĐ):** $D = \mathbb{R}$.
- **Bước 2 (Đạo hàm):** Ta có $y' = 3x^2 - 6x = 3x(x - 2)$.
- Cho $y' = 0 \Leftrightarrow 3x(x - 2) = 0 \Leftrightarrow x = 0$ hoặc $x = 2$.
- **Bước 3 (Bảng xét dấu $y'$):**
- - Trên các khoảng $(-\infty; 0)$ và $(2; +\infty)$: $y' > 0$.
- - Trên khoảng $(0; 2)$: $y' < 0$.
- **Bước 4 (Kết luận):**
- - Hàm số đồng biến trên các khoảng $(-\infty; 0)$ và $(2; +\infty)$.
- - Hàm số nghịch biến trên khoảng $(0; 2)$.

#### Bài 1.2 [Mức 1: Nhận biết]
- **Đề bài:** Cho hàm số phân thức bậc nhất trên bậc nhất $y = \dfrac{2x + 1}{x - 1}$. Tìm các khoảng đồng biến, nghịch biến của hàm số.
- **Phương pháp & Gợi ý giải:** Tìm TXĐ $D = \mathbb{R} \setminus \{1\}$, tính đạo hàm theo công thức $\left(\dfrac{ax+b}{cx+d}\right)' = \dfrac{ad-bc}{(cx+d)^2}$.
- **Lời giải chi tiết từng bước:**
- **Bước 1 (TXĐ):** $D = \mathbb{R} \setminus \{1\}$.
- **Bước 2 (Đạo hàm):** $y' = \dfrac{2(-1) - 1(1)}{(x - 1)^2} = \dfrac{-3}{(x - 1)^2}$.
- **Bước 3 (Xét dấu):** Vì $-3 < 0$ và $(x - 1)^2 > 0, \forall x \ne 1$, nên $y' < 0, \forall x \in D$.
- **Bước 4 (Kết luận):** Hàm số nghịch biến trên từng khoảng xác định $(-\infty; 1)$ và $(1; +\infty)$.

#### Bài 1.3 [Mức 1: Nhận biết]
- **Đề bài:** Tìm tọa độ các điểm cực đại và điểm cực tiểu của đồ thị hàm số $y = -x^3 + 3x - 1$.
- **Phương pháp & Gợi ý giải:** Tính $y'$, tìm nghiệm, tính giá trị cực trị và xác định tọa độ điểm cực trị $(x; y)$.
- **Lời giải chi tiết từng bước:**
- **Bước 1 (TXĐ):** $D = \mathbb{R}$.
- **Bước 2 (Đạo hàm):** $y' = -3x^2 + 3 = -3(x^2 - 1) = 0 \Leftrightarrow x = 1$ hoặc $x = -1$.
- **Bước 3 (Xác định cực trị):**
- - Tại $x = 1$: $y'$ đổi dấu từ $+$ sang $-$, $y(1) = 1 \Rightarrow$ Điểm cực đại của đồ thị là $A(1; 1)$.
- - Tại $x = -1$: $y'$ đổi dấu từ $-$ sang $+$, $y(-1) = -3 \Rightarrow$ Điểm cực tiểu của đồ thị là $B(-1; -3)$.

#### Bài 1.4 [Mức 1: Nhận biết]
- **Đề bài:** Cho hàm số $y = f(x)$ xác định trên $\mathbb{R}$ có bảng xét dấu đạo hàm $f'(x)$: $f'(x) > 0$ trên $(-\infty; -2)$ và $(1; 3)$; $f'(x) < 0$ trên $(-2; 1)$ và $(3; +\infty)$; $f'(x) = 0$ tại $x = -2, 1, 3$. Hãy xác định các khoảng đồng biến, nghịch biến và các điểm cực trị của hàm số.
- **Phương pháp & Gợi ý giải:** Đọc trực tiếp dấu của đạo hàm: $f' > 0$ là đồng biến, $f' < 0$ là nghịch biến; đổi dấu $+$ sang $-$ là cực đại, $-$ sang $+$ là cực tiểu.
- **Lời giải chi tiết từng bước:**
- **Khoảng đồng biến:** Hàm số đồng biến trên các khoảng $(-\infty; -2)$ và $(1; 3)$ (do $f'(x) > 0$).
- **Khoảng nghịch biến:** Hàm số nghịch biến trên các khoảng $(-2; 1)$ và $(3; +\infty)$ (do $f'(x) < 0$).
- **Điểm cực đại:** Hàm số đạt cực đại tại $x = -2$ và $x = 3$.
- **Điểm cực tiểu:** Hàm số đạt cực tiểu tại $x = 1$.

#### Bài 1.5 [Mức 2: Thông hiểu]
- **Đề bài:** Cho hàm số phân thức bậc hai trên bậc nhất $y = \dfrac{x^2 - 2x + 5}{x - 1}$. Lập bảng biến thiên và tìm các giá trị cực trị của hàm số.
- **Phương pháp & Gợi ý giải:** Tính đạo hàm bằng quy tắc thương, giải phương trình $y' = 0$, tính giá trị $y(-1)$ và $y(3)$.
- **Lời giải chi tiết từng bước:**
- **Bước 1 (TXĐ):** $D = \mathbb{R} \setminus \{1\}$.
- **Bước 2 (Đạo hàm):** $y' = \dfrac{(2x - 2)(x - 1) - (x^2 - 2x + 5)}{(x - 1)^2} = \dfrac{x^2 - 2x - 3}{(x - 1)^2}$.
- $y' = 0 \Leftrightarrow x = -1$ hoặc $x = 3$.
- **Bước 3 (Bảng biến thiên):** $y' > 0$ trên $(-\infty; -1)$ và $(3; +\infty)$; $y' < 0$ trên $(-1; 1)$ và $(1; 3)$.
- **Bước 4 (Kết luận):**
- - Hàm số đồng biến trên $(-\infty; -1)$ và $(3; +\infty)$; nghịch biến trên $(-1; 1)$ và $(1; 3)$.
- - Giá trị cực đại $y_{CĐ} = y(-1) = -4$; giá trị cực tiểu $y_{CT} = y(3) = 4$.

#### Bài 1.6 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm tất cả các giá trị của tham số thực $m$ để hàm số $y = \dfrac{1}{3}x^3 - mx^2 + (m^2 - 4)x + 5$ đồng biến trên toàn trục số $\mathbb{R}$.
- **Phương pháp & Gợi ý giải:** Hàm bậc ba với $a > 0$ đồng biến trên $\mathbb{R} \Leftrightarrow y' \ge 0, \forall x \Leftrightarrow \Delta'_{y'} \le 0$.
- **Lời giải chi tiết từng bước:**
- **Bước 1:** $D = \mathbb{R}$. Đạo hàm $y' = x^2 - 2mx + m^2 - 4$.
- **Bước 2:** Hàm số đồng biến trên $\mathbb{R} \Leftrightarrow y' \ge 0, \forall x \in \mathbb{R} \Leftrightarrow \Delta' \le 0$ (vì hệ số $a = 1 > 0$).
- **Bước 3:** Ta có $\Delta' = (-m)^2 - 1(m^2 - 4) = 4 > 0, \forall m$.
- **Bước 4:** Vì $\Delta' = 4 > 0$ với mọi $m$ nên $y' = 0$ luôn có 2 nghiệm phân biệt và đổi dấu. Vậy không tồn tại giá trị nào của tham số $m$ ($m \in \emptyset$).

#### Bài 1.7 [Mức 2: Thông hiểu]
- **Đề bài:** Cho hàm số $y = f(x)$ xác định trên $\mathbb{R}$ có $f'(x) = x(x - 1)^2(x + 2)^3(x - 4)^5$. Tìm số điểm cực trị và phân loại các điểm cực đại, cực tiểu của hàm số.
- **Phương pháp & Gợi ý giải:** Chỉ các nghiệm bội lẻ mới làm $f'$ đổi dấu; nghiệm bội chẵn không làm đổi dấu.
- **Lời giải chi tiết từng bước:**
- $f'(x) = 0 \Leftrightarrow x \in \{0; 1; -2; 4\}$.
- - Nghiệm $x = 1$ có bội 2 (chẵn) nên $f'(x)$ không đổi dấu qua $x = 1$ (không là cực trị).
- - Các nghiệm $x = 0$ (bội 1), $x = -2$ (bội 3), $x = 4$ (bội 5) là nghiệm bội lẻ nên là các điểm cực trị $\Rightarrow$ Hàm số có đúng $3$ điểm cực trị.
- Xét dấu: $f'(x)$ đổi dấu từ $-$ sang $+$ qua $x = -2$ và $x = 4$ (điểm cực tiểu); đổi dấu từ $+$ sang $-$ qua $x = 0$ (điểm cực đại).

#### Bài 1.8 [Mức 3: Vận dụng]
- **Đề bài:** Tìm tất cả các giá trị của tham số thực $m$ để hàm số $y = \dfrac{mx - 4}{x - m}$ đồng biến trên khoảng $(2; +\infty)$.
- **Phương pháp & Gợi ý giải:** Điều kiện gồm: Đạo hàm $y' > 0$ và nghiệm của mẫu $x_0 = m \notin (2; +\infty)$.
- **Lời giải chi tiết từng bước:**
- **TXĐ:** $D = \mathbb{R} \setminus \{m\}$. Đạo hàm $y' = \dfrac{-m^2 + 4}{(x - m)^2}$.
- Hàm số đồng biến trên $(2; +\infty) \Leftrightarrow \begin{cases} y' > 0, \forall x \in (2; +\infty) \\ m \notin (2; +\infty) \end{cases} \Leftrightarrow \begin{cases} -m^2 + 4 > 0 \\ m \le 2 \end{cases} \Leftrightarrow \begin{cases} -2 < m < 2 \\ m \le 2 \end{cases}$.
- Kết luận: $-2 < m < 2$ (hay $m \in (-2; 2)$).

#### Bài 1.9 [Mức 3: Vận dụng]
- **Đề bài:** Cho hàm số $y = x^3 - 3x^2 + m$. Tìm tất cả các giá trị của tham số $m$ để đồ thị hàm số có hai điểm cực trị $A, B$ sao cho tam giác $OAB$ vuông tại gốc tọa độ $O(0; 0)$.
- **Phương pháp & Gợi ý giải:** Tìm tọa độ $A(0; m)$ và $B(2; m-4)$. Tam giác $OAB$ vuông tại $O \Leftrightarrow \vec{OA} \cdot \vec{OB} = 0$ và $A, B \ne O$.
- **Lời giải chi tiết từng bước:**
- $y' = 3x^2 - 6x = 0 \Leftrightarrow x = 0$ hoặc $x = 2$.
- Tọa độ hai điểm cực trị: $A(0; m)$ và $B(2; m - 4)$.
- Ta có $\vec{OA} = (0; m)$, $\vec{OB} = (2; m - 4)$.
- Tam giác $OAB$ vuông tại $O \Leftrightarrow \begin{cases} A, B \ne O \\ \vec{OA} \cdot \vec{OB} = 0 \end{cases} \Leftrightarrow \begin{cases} m \ne 0 \\ 0(2) + m(m - 4) = 0 \end{cases} \Leftrightarrow \begin{cases} m \ne 0 \\ m(m - 4) = 0 \end{cases} \Leftrightarrow m = 4$.
- Kết luận: $m = 4$.

#### Bài 1.10 [Mức 3: Vận dụng]
- **Đề bài:** Cho hàm số $y = f(x)$ có đạo hàm $f'(x) = x(x - 2)$. Xét tính đơn điệu và tìm các điểm cực trị của hàm số hợp $g(x) = f(x^2 - 2x - 3)$.
- **Phương pháp & Gợi ý giải:** Tính $g'(x) = (2x - 2)f'(x^2 - 2x - 3)$, giải phương trình hoành độ và xét dấu theo nghiệm bội lẻ.
- **Lời giải chi tiết từng bước:**
- $g'(x) = (2x - 2) \cdot f'(x^2 - 2x - 3)$.
- $g'(x) = 0 \Leftrightarrow 2x - 2 = 0 \Leftrightarrow x = 1$ hoặc $x^2 - 2x - 3 = 0 \Leftrightarrow x = -1, x = 3$ hoặc $x^2 - 2x - 3 = 2 \Leftrightarrow x = 1 \pm \sqrt{6}$.
- Cả 5 nghiệm đều là nghiệm đơn phân biệt: $1-\sqrt{6} < -1 < 1 < 3 < 1+\sqrt{6}$.
- Thử dấu $x = 4 > 1+\sqrt{6} \Rightarrow g'(4) = 6 \cdot f'(5) = 6 \cdot 15 > 0$.
- - Hàm số đồng biến trên: $(1-\sqrt{6}; -1)$, $(1; 3)$ và $(1+\sqrt{6}; +\infty)$.
- - Hàm số nghịch biến trên: $(-\infty; 1-\sqrt{6})$, $(-1; 1)$ và $(3; 1+\sqrt{6})$.
- - Cực tiểu tại $x = 1 - \sqrt{6}, x = 1, x = 1 + \sqrt{6}$; cực đại tại $x = -1, x = 3$.

---

### 2. Dạng 2 (SGK Toán 12 KNTT): Giá trị lớn nhất và nhỏ nhất của hàm số — 10 Bài tự luận phân tầng
#### Bài 2.1 [Mức 1: Nhận biết]
- **Đề bài:** Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số $y = x^3 - 3x + 2$ trên đoạn $[0; 2]$.
- **Phương pháp & Gợi ý giải:** Tính đạo hàm $y'$, tìm nghiệm thuộc đoạn $[0; 2]$, tính giá trị tại các điểm tới hạn và hai đầu mút.
- **Lời giải chi tiết từng bước:**
- Hàm số liên tục trên $[0; 2]$. Ta có $y' = 3x^2 - 3 = 0 \Leftrightarrow x = 1$ (thuộc $[0; 2]$) hoặc $x = -1$ (loại).
- Tính các giá trị: $y(0) = 2$, $y(1) = 0$, $y(2) = 2^3 - 3(2) + 2 = 4$.
- So sánh các giá trị: $\max_{[0; 2]} y = 4$ tại $x = 2$; $\min_{[0; 2]} y = 0$ tại $x = 1$.

#### Bài 2.2 [Mức 1: Nhận biết]
- **Đề bài:** Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số $y = \dfrac{2x - 1}{x + 1}$ trên đoạn $[0; 3]$.
- **Phương pháp & Gợi ý giải:** Hàm phân thức bậc nhất trên bậc nhất luôn đơn điệu trên từng đoạn không chứa nghiệm mẫu, GTLN và GTNN luôn đạt tại hai đầu mút.
- **Lời giải chi tiết từng bước:**
- Hàm số liên tục trên $[0; 3]$ (mẫu $x + 1 = 0 \Leftrightarrow x = -1 \notin [0; 3]$).
- Đạo hàm $y' = \dfrac{2(1) - (-1)(1)}{(x + 1)^2} = \dfrac{3}{(x + 1)^2} > 0, \forall x \in [0; 3]$.
- Vì hàm số đồng biến trên $[0; 3]$, nên:
- - $\min_{[0; 3]} y = y(0) = \dfrac{-1}{1} = -1$ tại $x = 0$.
- - $\max_{[0; 3]} y = y(3) = \dfrac{2(3) - 1}{3 + 1} = \dfrac{5}{4}$ tại $x = 3$.

#### Bài 2.3 [Mức 1: Nhận biết]
- **Đề bài:** Cho hàm số $y = f(x)$ liên tục trên đoạn $[-2; 3]$ có bảng biến thiên: $f(-2) = 1$, $f(-1) = 5$, $f(1) = -2$, $f(3) = 4$. Xác định GTLN, GTNN của hàm số trên đoạn $[-2; 3]$ và chỉ rõ đạt được tại điểm nào.
- **Phương pháp & Gợi ý giải:** So sánh các giá trị tại các điểm cực trị và hai đầu mút đã cho trong bảng biến thiên.
- **Lời giải chi tiết từng bước:**
- Trên đoạn $[-2; 3]$, tập hợp các giá trị của hàm số là $[-2; 5]$.
- Giá trị lớn nhất: $\max_{[-2; 3]} f(x) = 5$ đạt tại $x = -1$.
- Giá trị nhỏ nhất: $\min_{[-2; 3]} f(x) = -2$ đạt tại $x = 1$.

#### Bài 2.4 [Mức 1: Nhận biết]
- **Đề bài:** Tìm giá trị nhỏ nhất của hàm số $y = x + \dfrac{4}{x}$ trên khoảng $(0; +\infty)$.
- **Phương pháp & Gợi ý giải:** Có thể dùng đạo hàm lập BBT trên khoảng $(0; +\infty)$ hoặc dùng bất đẳng thức Cauchy cho hai số dương $x$ và $\dfrac{4}{x}$.
- **Lời giải chi tiết từng bước:**
- **Cách 1 (Đạo hàm):** Với $x > 0$, $y' = 1 - \dfrac{4}{x^2} = \dfrac{x^2 - 4}{x^2} = 0 \Leftrightarrow x = 2$ (do $x > 0$).
- Lập BBT trên $(0; +\infty)$: Hàm số nghịch biến trên $(0; 2)$, đồng biến trên $(2; +\infty)$.
- Do đó $\min_{(0; +\infty)} y = y(2) = 2 + \dfrac{4}{2} = 4$ tại $x = 2$.
- **Cách 2 (BĐT Cauchy):** Vì $x > 0$ và $\dfrac{4}{x} > 0$, ta có $x + \dfrac{4}{x} \ge 2\sqrt{x \cdot \dfrac{4}{x}} = 4$. Dấu '=' xảy ra khi $x = \dfrac{4}{x} \Leftrightarrow x = 2$.

#### Bài 2.5 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số chứa căn $y = \sqrt{4 - x^2} + x$ trên đoạn $[-2; 2]$.
- **Phương pháp & Gợi ý giải:** Tính đạo hàm $y' = \dfrac{-x}{\sqrt{4-x^2}} + 1$, giải $y' = 0$ đưa về $\sqrt{4-x^2} = x$.
- **Lời giải chi tiết từng bước:**
- Hàm số xác định và liên tục trên $[-2; 2]$. Với $x \in (-2; 2)$, ta có:
- $y' = \dfrac{-x}{\sqrt{4 - x^2}} + 1$.
- $y' = 0 \Leftrightarrow \sqrt{4 - x^2} = x \Leftrightarrow \begin{cases} x \ge 0 \\ 4 - x^2 = x^2 \end{cases} \Leftrightarrow \begin{cases} x \ge 0 \\ 2x^2 = 4 \end{cases} \Leftrightarrow x = \sqrt{2} \in [-2; 2]$.
- Tính giá trị: $y(-2) = -2$, $y(2) = 2$, $y(\sqrt{2}) = \sqrt{4 - 2} + \sqrt{2} = 2\sqrt{2}$.
- Kết luận: $\max_{[-2; 2]} y = 2\sqrt{2}$ tại $x = \sqrt{2}$; $\min_{[-2; 2]} y = -2$ tại $x = -2$.

#### Bài 2.6 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số $y = \sin^2 x - 2\cos x + 3$ trên đoạn $[0; \pi]$.
- **Phương pháp & Gợi ý giải:** Đổi $\sin^2 x = 1 - \cos^2 x$, đặt ẩn phụ $t = \cos x$ với điều kiện $t \in [-1; 1]$.
- **Lời giải chi tiết từng bước:**
- Ta có $\sin^2 x = 1 - \cos^2 x$, do đó hàm số viết lại thành $y = -\cos^2 x - 2\cos x + 4$.
- Đặt $t = \cos x$. Khi $x \in [0; \pi]$ thì $t \in [-1; 1]$.
- Bài toán trở thành tìm GTLN, GTNN của $f(t) = -t^2 - 2t + 4$ trên đoạn $[-1; 1]$.
- Đạo hàm $f'(t) = -2t - 2 = 0 \Leftrightarrow t = -1$.
- Tính giá trị tại các điểm biên: $f(-1) = -(-1)^2 - 2(-1) + 4 = 5$, $f(1) = -(1)^2 - 2(1) + 4 = 1$.
- Kết luận: GTLN là $5$ (khi $t = -1 \Leftrightarrow x = \pi$); GTNN là $1$ (khi $t = 1 \Leftrightarrow x = 0$).

#### Bài 2.7 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số $y = \dfrac{x^2 + 3}{x - 1}$ trên đoạn $[2; 4]$.
- **Phương pháp & Gợi ý giải:** Tính đạo hàm bằng quy tắc thương, tìm nghiệm trong khoảng $(2; 4)$, tính và so sánh $y(2), y(3), y(4)$.
- **Lời giải chi tiết từng bước:**
- Hàm số liên tục trên $[2; 4]$. Đạo hàm:
- $y' = \dfrac{2x(x - 1) - (x^2 + 3)}{(x - 1)^2} = \dfrac{x^2 - 2x - 3}{(x - 1)^2}$.
- Cho $y' = 0 \Leftrightarrow x^2 - 2x - 3 = 0 \Leftrightarrow x = 3 \in [2; 4]$ (nghiệm $x = -1$ bị loại).
- Tính giá trị: $y(2) = \dfrac{2^2 + 3}{2 - 1} = 7$, $y(3) = \dfrac{3^2 + 3}{3 - 1} = 6$, $y(4) = \dfrac{4^2 + 3}{4 - 1} = \dfrac{19}{3} \approx 6{,}33$.
- Kết luận: $\max_{[2; 4]} y = 7$ tại $x = 2$; $\min_{[2; 4]} y = 6$ tại $x = 3$.

#### Bài 2.8 [Mức 3: Vận dụng]
- **Đề bài:** Tìm tất cả các giá trị của tham số $m$ để giá trị nhỏ nhất của hàm số $y = x^3 - 3x^2 + m$ trên đoạn $[1; 3]$ bằng $-5$.
- **Phương pháp & Gợi ý giải:** Tìm nghiệm của $y'=0$ trong $[1; 3]$, lập biểu thức GTNN theo $m$, giải phương trình $\min = -5$.
- **Lời giải chi tiết từng bước:**
- $y' = 3x^2 - 6x = 3x(x - 2) = 0 \Leftrightarrow x = 0$ (loại vì $\notin [1; 3]$) hoặc $x = 2 \in [1; 3]$.
- Tính các giá trị tại điểm tới hạn và mút đoạn:
- $y(1) = 1^3 - 3(1)^2 + m = m - 2$.
- $y(2) = 2^3 - 3(2)^2 + m = m - 4$.
- $y(3) = 3^3 - 3(3)^2 + m = m$.
- Vì $m - 4 < m - 2 < m$ nên $\min_{[1; 3]} y = y(2) = m - 4$.
- Theo đề bài: $\min_{[1; 3]} y = -5 \Leftrightarrow m - 4 = -5 \Leftrightarrow m = -1$.
- Kết luận: $m = -1$.

#### Bài 2.9 [Mức 3: Vận dụng]
- **Đề bài:** Cho hàm số $y = \left|\dfrac{x - m}{x + 1}\right|$. Tìm tất cả các giá trị thực của tham số $m$ để giá trị lớn nhất của hàm số trên đoạn $[0; 1]$ đạt giá trị nhỏ nhất.
- **Phương pháp & Gợi ý giải:** Xét hàm $u(x) = \dfrac{x-m}{x+1}$, tính GTLN của $|u(x)|$ bằng $\max\{|u(0)|, |u(1)|\}$, áp dụng BĐT $\max\{|A|, |B|\} \ge \dfrac{|A-B|}{2}$.
- **Lời giải chi tiết từng bước:**
- Xét hàm $u(x) = \dfrac{x - m}{x + 1}$ trên đoạn $[0; 1]$ ($m \ne -1$). Đạo hàm $u'(x) = \dfrac{1 + m}{(x + 1)^2}$.
- - Hàm số $u(x)$ đơn điệu trên $[0; 1]$, do đó $u(x)$ đạt cực trị tại hai đầu mút $x = 0$ và $x = 1$.
- - Ta có $u(0) = -m$ và $u(1) = \dfrac{1 - m}{2}$.
- Khi đó $\max_{[0; 1]} |u(x)| = \max\{|u(0)|, |u(1)|\} = \max\left\{|m|, \left|\dfrac{1 - m}{2}\right|\right\}$.
- Đặt $M = \max\left\{|m|, \left|\dfrac{m - 1}{2}\right|\right\}$. Ta có $M \ge |m|$ và $M \ge \left|\dfrac{m - 1}{2}\right| = \dfrac{|1 - m|}{2}$.
- Áp dụng BĐT tam giác: $2M = |2m| + |1 - m| \ge |2m + (1 - m)| = |m + 1|$, hoặc xét phương trình $|m| = \dfrac{|1 - m|}{2} \Leftrightarrow 2|m| = |1 - m| \Leftrightarrow \begin{bmatrix} 2m = 1 - m \\ 2m = m - 1 \end{bmatrix} \Leftrightarrow m = \dfrac{1}{3}$ hoặc $m = -1$ (loại vì $m \ne -1$).
- - Với $m = \dfrac{1}{3} \Rightarrow |u(0)| = \dfrac{1}{3}$, $|u(1)| = \dfrac{1}{3} \Rightarrow M = \dfrac{1}{3}$.
- Kết luận: $m = \dfrac{1}{3}$.

#### Bài 2.10 [Mức 3: Vận dụng]
- **Đề bài:** Một người nông dân có $120\text{ m}$ hàng rào lưới thép muốn rào một khu đất hình chữ nhật giáp bờ sông thẳng (bờ sông không cần rào). Hãy xác định kích thước khu đất để diện tích rào được là lớn nhất và tính diện tích lớn nhất đó.
- **Phương pháp & Gợi ý giải:** Gọi $x$ là chiều rộng vuông góc với bờ sông ($0 < x < 60$), chiều dài song song bờ sông là $120 - 2x$, lập hàm diện tích $S(x)$ và tìm GTLN.
- **Lời giải chi tiết từng bước:**
- Gọi chiều rộng của mảnh đất (hai cạnh vuông góc bờ sông) là $x$ ($x > 0$, đơn vị mét).
- - Chiều dài của mảnh đất (cạnh song song với bờ sông) là $120 - 2x$ (mét).
- - Điều kiện: $0 < x < 60$.
- Diện tích của khu đất là hàm số: $S(x) = x(120 - 2x) = -2x^2 + 120x$ ($0 < x < 60$).
- Đạo hàm: $S'(x) = -4x + 120 = 0 \Leftrightarrow x = 30\text{ m}$ (thỏa mãn điều kiện).
- Lập BBT hoặc nhận xét tam thức bậc hai có đỉnh tại $x = 30$:
- Hàm số đạt giá trị lớn nhất tại $x = 30\text{ m}$.
- - Chiều dài tương ứng là: $120 - 2(30) = 60\text{ m}$.
- - Diện tích lớn nhất là: $S_{\max} = S(30) = 30 \cdot 60 = 1800\text{ m}^2$.
- Kết luận: Kích thước tối ưu là chiều rộng $30\text{ m}$, chiều dài $60\text{ m}$; diện tích lớn nhất là $1800\text{ m}^2$.

---

### 3. Dạng 3 (SGK Toán 12 KNTT): Đường tiệm cận của đồ thị hàm số — 10 Bài tự luận phân tầng
#### Bài 3.1 [Mức 1: Nhận biết]
- **Đề bài:** Tìm phương trình các đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{3x - 1}{x + 2}$.
- **Phương pháp & Gợi ý giải:** Tính giới hạn tại điểm làm mẫu số bằng 0 để tìm TCĐ, và giới hạn khi $x \to \pm\infty$ để tìm TCN.
- **Lời giải chi tiết từng bước:**
- **Tiệm cận đứng:** Mẫu số $x + 2 = 0 \Leftrightarrow x = -2$.
- Ta có $\lim_{x \to (-2)^+} \dfrac{3x - 1}{x + 2} = -\infty$ và $\lim_{x \to (-2)^-} \dfrac{3x - 1}{x + 2} = +\infty$. Do đó $x = -2$ là đường tiệm cận đứng.
- **Tiệm cận ngang:** Ta có $\lim_{x \to \pm\infty} \dfrac{3x - 1}{x + 2} = \lim_{x \to \pm\infty} \dfrac{3 - 1/x}{1 + 2/x} = 3$. Do đó $y = 3$ là đường tiệm cận ngang.
- **Kết luận:** TCĐ: $x = -2$; TCN: $y = 3$.

#### Bài 3.2 [Mức 1: Nhận biết]
- **Đề bài:** Cho hàm số $y = f(x)$ xác định trên $\mathbb{R} \setminus \{1\}$ có $\lim_{x \to +\infty} f(x) = 2$, $\lim_{x \to -\infty} f(x) = -1$ và $\lim_{x \to 1^+} f(x) = +\infty$. Hãy chỉ rõ tất cả các đường tiệm cận ngang và tiệm cận đứng của đồ thị hàm số.
- **Phương pháp & Gợi ý giải:** Theo định nghĩa: $\lim_{x \to \pm\infty} f(x) = y_0 \Rightarrow y = y_0$ là TCN; $\lim_{x \to x_0} f(x) = \pm\infty \Rightarrow x = x_0$ là TCĐ.
- **Lời giải chi tiết từng bước:**
- **Tiệm cận ngang:**
- - Vì $\lim_{x \to +\infty} f(x) = 2$ nên đường thẳng $y = 2$ là tiệm cận ngang.
- - Vì $\lim_{x \to -\infty} f(x) = -1$ nên đường thẳng $y = -1$ là tiệm cận ngang.
- **Tiệm cận đứng:**
- - Vì $\lim_{x \to 1^+} f(x) = +\infty$ nên đường thẳng $x = 1$ là tiệm cận đứng.
- **Kết luận:** Đồ thị hàm số có 2 đường tiệm cận ngang là $y = 2, y = -1$ và 1 đường tiệm cận đứng là $x = 1$.

#### Bài 3.3 [Mức 1: Nhận biết]
- **Đề bài:** Tìm phương trình đường tiệm cận xiên của đồ thị hàm số $y = \dfrac{x^2 + 2x - 3}{x + 1}$.
- **Phương pháp & Gợi ý giải:** Chia đa thức tử số cho mẫu số để viết $y = ax + b + \dfrac{r}{x+1}$. Khi đó $y = ax + b$ là tiệm cận xiên.
- **Lời giải chi tiết từng bước:**
- Thực hiện phép chia đa thức tử số cho mẫu số:
- $x^2 + 2x - 3 = (x + 1)(x + 1) - 4 = x^2 + 2x + 1 - 4$.
- Do đó $y = x + 1 - \dfrac{4}{x + 1}$.
- Xét giới hạn: $\lim_{x \to \pm\infty} [y - (x + 1)] = \lim_{x \to \pm\infty} \left(-\dfrac{4}{x + 1}\right) = 0$.
- **Kết luận:** Đường tiệm cận xiên của đồ thị hàm số là đường thẳng $y = x + 1$.

#### Bài 3.4 [Mức 1: Nhận biết]
- **Đề bài:** Tìm tọa độ giao điểm $I$ của hai đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{2x + 5}{x - 3}$.
- **Phương pháp & Gợi ý giải:** Xác định phương trình đường TCĐ $x = x_0$ và TCN $y = y_0$, suy ra tọa độ giao điểm $I(x_0; y_0)$.
- **Lời giải chi tiết từng bước:**
- Tiệm cận đứng của đồ thị hàm số là đường thẳng $x = 3$ (nghiệm của mẫu số $x - 3 = 0$).
- Tiệm cận ngang của đồ thị hàm số là đường thẳng $y = 2$ (giới hạn $\lim_{x \to \pm\infty} y = 2$).
- Giao điểm của hai đường tiệm cận là nghiệm của hệ $\begin{cases} x = 3 \\ y = 2 \end{cases} \Rightarrow I(3; 2)$.
- **Kết luận:** Tọa độ giao điểm hai đường tiệm cận là $I(3; 2)$.

#### Bài 3.5 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm tất cả các đường tiệm cận (đứng, xiên) của đồ thị hàm số $y = \dfrac{2x^2 - 3x + 1}{x - 2}$.
- **Phương pháp & Gợi ý giải:** Tìm nghiệm mẫu số suy ra TCĐ; thực hiện phép chia đa thức để viết $y = ax + b + \dfrac{r}{x-2}$ suy ra TCX.
- **Lời giải chi tiết từng bước:**
- **Tiệm cận đứng:** Nghiệm của mẫu số là $x = 2$. Thay $x = 2$ vào tử: $2(2)^2 - 3(2) + 1 = 3 \ne 0$.
- Do đó $\lim_{x \to 2^+} y = +\infty$ và $\lim_{x \to 2^-} y = -\infty \Rightarrow x = 2$ là đường tiệm cận đứng.
- **Tiệm cận xiên:** Thực hiện phép chia đa thức tử cho mẫu:
- $2x^2 - 3x + 1 = (2x + 1)(x - 2) + 3 \Rightarrow y = 2x + 1 + \dfrac{3}{x - 2}$.
- Vì $\lim_{x \to \pm\infty} [y - (2x + 1)] = \lim_{x \to \pm\infty} \dfrac{3}{x - 2} = 0$, nên đường thẳng $y = 2x + 1$ là tiệm cận xiên.
- **Kết luận:** Đồ thị hàm số có tiệm cận đứng $x = 2$ và tiệm cận xiên $y = 2x + 1$.

#### Bài 3.6 [Mức 2: Thông hiểu]
- **Đề bài:** Tìm tất cả các đường tiệm cận ngang của đồ thị hàm số chứa căn thức $y = \dfrac{\sqrt{x^2 + 2x + 3}}{2x - 1}$.
- **Phương pháp & Gợi ý giải:** Tính giới hạn tại $+\infty$ và $-\infty$. Lưu ý khi $x \to -\infty$ thì $\sqrt{x^2} = |x| = -x$.
- **Lời giải chi tiết từng bước:**
- Tập xác định: $x^2 + 2x + 3 = (x + 1)^2 + 2 > 0, \forall x$. Mẫu số $2x - 1 \ne 0 \Leftrightarrow x \ne 1/2$. Do đó $D = \mathbb{R} \setminus \{1/2\}$.
- Giới hạn khi $x \to +\infty$ ($x > 0 \Rightarrow \sqrt{x^2} = x$):
- $\lim_{x \to +\infty} \dfrac{\sqrt{x^2 + 2x + 3}}{2x - 1} = \lim_{x \to +\infty} \dfrac{x\sqrt{1 + 2/x + 3/x^2}}{x(2 - 1/x)} = \dfrac{\sqrt{1}}{2} = \dfrac{1}{2}$.
- Do đó đường thẳng $y = \dfrac{1}{2}$ là một tiệm cận ngang.
- Giới hạn khi $x \to -\infty$ ($x < 0 \Rightarrow \sqrt{x^2} = -x$):
- $\lim_{x \to -\infty} \dfrac{\sqrt{x^2 + 2x + 3}}{2x - 1} = \lim_{x \to -\infty} \dfrac{-x\sqrt{1 + 2/x + 3/x^2}}{x(2 - 1/x)} = -\dfrac{1}{2}$.
- Do đó đường thẳng $y = -\dfrac{1}{2}$ là một tiệm cận ngang.
- **Kết luận:** Đồ thị hàm số có đúng 2 đường tiệm cận ngang là $y = \dfrac{1}{2}$ và $y = -\dfrac{1}{2}$.

#### Bài 3.7 [Mức 2: Thông hiểu]
- **Đề bài:** Xác định số đường tiệm cận đứng của đồ thị hàm số $y = \dfrac{x - 1}{x^2 - 3x + 2}$. Giải thích chi tiết.
- **Phương pháp & Gợi ý giải:** Phân tích mẫu số thành nhân tử $(x-1)(x-2)$, xét tính triệt tiêu nghiệm chung $x = 1$.
- **Lời giải chi tiết từng bước:**
- Tập xác định: Mẫu $x^2 - 3x + 2 = 0 \Leftrightarrow x = 1$ hoặc $x = 2 \Rightarrow D = \mathbb{R} \setminus \{1; 2\}$.
- Phân tích hàm số: Với mọi $x \ne 1$ và $x \ne 2$, ta có:
- $y = \dfrac{x - 1}{(x - 1)(x - 2)} = \dfrac{1}{x - 2}$.
- Xét giới hạn tại hai điểm nghi ngờ:
- - Tại $x = 1$: $\lim_{x \to 1} y = \lim_{x \to 1} \dfrac{1}{x - 2} = \dfrac{1}{1 - 2} = -1$ (giới hạn hữu hạn). Do đó $x = 1$ KHÔNG phải là tiệm cận đứng.
- - Tại $x = 2$: $\lim_{x \to 2^+} y = \lim_{x \to 2^+} \dfrac{1}{x - 2} = +\infty$ và $\lim_{x \to 2^-} y = -\infty$. Do đó $x = 2$ LÀ tiệm cận đứng duy nhất.
- **Kết luận:** Đồ thị hàm số có đúng $1$ đường tiệm cận đứng là $x = 2$.

#### Bài 3.8 [Mức 3: Vận dụng]
- **Đề bài:** Tìm tất cả các giá trị của tham số thực $m$ để đồ thị hàm số $y = \dfrac{x - 1}{x^2 - 2mx + m + 2}$ có đúng hai đường tiệm cận đứng.
- **Phương pháp & Gợi ý giải:** Đồ thị có 2 TCĐ khi và chỉ khi mẫu số $g(x) = x^2 - 2mx + m + 2 = 0$ có hai nghiệm phân biệt khác 1 (nghiệm của tử số).
- **Lời giải chi tiết từng bước:**
- Đặt $g(x) = x^2 - 2mx + m + 2$. Tử số có nghiệm là $x = 1$.
- Đồ thị hàm số có đúng hai đường tiệm cận đứng khi và chỉ khi phương trình $g(x) = 0$ có 2 nghiệm phân biệt khác $1$.
- Điều này tương đương với:
- $\begin{cases} \Delta' > 0 \\ g(1) \ne 0 \end{cases} \Leftrightarrow \begin{cases} (-m)^2 - 1(m + 2) > 0 \\ 1^2 - 2m(1) + m + 2 \ne 0 \end{cases} \Leftrightarrow \begin{cases} m^2 - m - 2 > 0 \\ 3 - m \ne 0 \end{cases}$.
- Giải bất phương trình $m^2 - m - 2 > 0 \Leftrightarrow m < -1$ hoặc $m > 2$.
- Kết hợp điều kiện $m \ne 3$:
- Ta được: $m < -1$ hoặc $\begin{cases} m > 2 \\ m \ne 3 \end{cases}$.
- **Kết luận:** Các giá trị $m$ cần tìm là $m \in (-\infty; -1) \cup (2; 3) \cup (3; +\infty)$.

#### Bài 3.9 [Mức 3: Vận dụng]
- **Đề bài:** Cho hàm số $y = \dfrac{x^2 - x + 1}{x - 1}$ có đồ thị $(C)$. Tìm điểm $M$ trên đồ thị $(C)$ sao cho khoảng cách từ $M$ đến đường tiệm cận xiên là nhỏ nhất.
- **Phương pháp & Gợi ý giải:** Tìm tiệm cận xiên $y = x$, lập công thức khoảng cách từ $M\left(x_0; x_0 + \dfrac{1}{x_0 - 1}\right)$ đến tiệm cận xiên.
- **Lời giải chi tiết từng bước:**
- Viết lại hàm số: $y = x + \dfrac{1}{x - 1}$.
- Đường tiệm cận xiên của $(C)$ là $\Delta: y = x \Leftrightarrow x - y = 0$.
- Điểm $M$ thuộc đồ thị $(C)$ có tọa độ $M\left(x_0; x_0 + \dfrac{1}{x_0 - 1}\right)$ với $x_0 \ne 1$.
- Khoảng cách từ $M$ đến đường tiệm cận xiên $\Delta$ là:
- $d(M, \Delta) = \dfrac{|x_0 - y_0|}{\sqrt{1^2 + (-1)^2}} = \dfrac{\left|x_0 - \left(x_0 + \dfrac{1}{x_0 - 1}\right)\right|}{\sqrt{2}} = \dfrac{1}{\sqrt{2}|x_0 - 1|}$.
- Khoảng cách $d(M, \Delta)$ tiến về $0$ khi $|x_0 - 1| \to +\infty$ (không có GTNN trên toàn bộ trục số nếu không giới hạn). Tuy nhiên, nếu xét bài toán khoảng cách đến cả hai tiệm cận: tích khoảng cách $d(M, \Delta_1) \cdot d(M, \Delta_2) = |x_0 - 1| \cdot \dfrac{1}{\sqrt{2}|x_0 - 1|} = \dfrac{1}{\sqrt{2}}$ là hằng số không đổi.

#### Bài 3.10 [Mức 3: Vận dụng]
- **Đề bài:** Tìm tất cả các giá trị của tham số $m$ để đường tiệm cận xiên của đồ thị hàm số $y = \dfrac{2x^2 + (m-1)x + 1}{x + 1}$ đi qua điểm $A(1; 5)$.
- **Phương pháp & Gợi ý giải:** Chia đa thức tìm phương trình tiệm cận xiên theo $m$, thay tọa độ điểm $A(1; 5)$ vào để tìm $m$.
- **Lời giải chi tiết từng bước:**
- Thực hiện phép chia đa thức tử cho mẫu $x + 1$:
- $2x^2 + (m-1)x + 1 = 2x(x + 1) + (m - 3)(x + 1) + (4 - m)$.
- Do đó $y = 2x + m - 3 + \dfrac{4 - m}{x + 1}$.
- Điều kiện để có tiệm cận xiên là phần dư $4 - m \ne 0 \Leftrightarrow m \ne 4$.
- Khi đó đường tiệm cận xiên là đường thẳng $d: y = 2x + m - 3$.
- Để đường tiệm cận xiên đi qua điểm $A(1; 5)$, thay $x = 1, y = 5$ vào phương trình $d$:
- $5 = 2(1) + m - 3 \Leftrightarrow 5 = m - 1 \Leftrightarrow m = 6$.
- Kiểm tra điều kiện: $m = 6 \ne 4$ (thỏa mãn).
- **Kết luận:** $m = 6$.

---

### 4. Dạng 4 (SGK Toán 12 KNTT): Khảo sát sự biến thiên và vẽ đồ thị hàm số — 10 Bài tự luận phân tầng
#### Bài 4.1 [Mức 1: Nhận biết]
- **Đề bài:** Khảo sát sự biến thiên và vẽ đồ thị của hàm số bậc ba $y = x^3 - 3x^2 + 2$.
- **Phương pháp & Gợi ý giải:** Tiến hành 3 bước chuẩn: 1) TXĐ, 2) Khảo sát sự biến thiên (giới hạn, đạo hàm, BBT), 3) Vẽ đồ thị (tìm điểm đặc biệt, giao trục, điểm uốn).
- **Lời giải chi tiết từng bước:**
- **1. Tập xác định:** $D = \mathbb{R}$.
- **2. Sự biến thiên:**
- - Giới hạn: $\lim_{x \to -\infty} y = -\infty$; $\lim_{x \to +\infty} y = +\infty$.
- - Đạo hàm: $y' = 3x^2 - 6x = 3x(x - 2) = 0 \Leftrightarrow x = 0$ hoặc $x = 2$.
- - Bảng biến thiên: Hàm số đồng biến trên $(-\infty; 0)$ và $(2; +\infty)$; nghịch biến trên $(0; 2)$. Cực đại tại $x = 0, y_{CĐ} = 2$; cực tiểu tại $x = 2, y_{CT} = -2$.
- **3. Đồ thị:** Đồ thị cắt $Oy$ tại $(0; 2)$, cắt $Ox$ tại $(1; 0)$ và $(1 \pm \sqrt{3}; 0)$. Điểm uốn $I(1; 0)$ là tâm đối xứng.

#### Bài 4.2 [Mức 1: Nhận biết]
- **Đề bài:** Khảo sát sự biến thiên và vẽ đồ thị của hàm số phân thức bậc nhất trên bậc nhất $y = \dfrac{x - 1}{x + 1}$.
- **Phương pháp & Gợi ý giải:** Tìm TXĐ $D = \mathbb{R}\setminus\{-1\}$, tính $y' = \dfrac{2}{(x+1)^2} > 0$, xác định TCĐ $x = -1$, TCN $y = 1$ và tâm đối xứng $I(-1; 1)$.
- **Lời giải chi tiết từng bước:**
- **1. Tập xác định:** $D = \mathbb{R} \setminus \{-1\}$.
- **2. Sự biến thiên:**
- - Tiệm cận: $\lim_{x \to \pm\infty} y = 1 \Rightarrow$ TCN $y = 1$. $\lim_{x \to (-1)^+} y = -\infty, \lim_{x \to (-1)^-} y = +\infty \Rightarrow$ TCĐ $x = -1$.
- - Đạo hàm: $y' = \dfrac{1(1) - (-1)(1)}{(x + 1)^2} = \dfrac{2}{(x + 1)^2} > 0, \forall x \ne -1$.
- - BBT: Hàm số đồng biến trên từng khoảng $(-\infty; -1)$ và $(-1; +\infty)$. Hàm số không có cực trị.
- **3. Đồ thị:** Giao $Ox$ tại $(1; 0)$, giao $Oy$ tại $(0; -1)$. Tâm đối xứng $I(-1; 1)$ là giao điểm 2 tiệm cận.

#### Bài 4.3 [Mức 1: Nhận biết]
- **Đề bài:** Tìm tọa độ tâm đối xứng của đồ thị hàm số phân thức $y = \dfrac{2x - 3}{x - 1}$ và tọa độ tâm đối xứng của đồ thị hàm số bậc ba $y = x^3 - 3x + 1$.
- **Phương pháp & Gợi ý giải:** Đồ thị phân thức có tâm đối xứng là giao 2 đường tiệm cận. Đồ thị bậc ba có tâm đối xứng là điểm uốn $x_0$ thỏa mãn $y''(x_0) = 0$.
- **Lời giải chi tiết từng bước:**
- Với hàm số phân thức $y = \dfrac{2x - 3}{x - 1}$:
- - Tiệm cận đứng $x = 1$, tiệm cận ngang $y = 2$.
- - Tâm đối xứng của đồ thị là giao điểm của hai đường tiệm cận: $I_1(1; 2)$.
- Với hàm số bậc ba $y = x^3 - 3x + 1$:
- - Ta có $y' = 3x^2 - 3 \Rightarrow y'' = 6x$.
- - Cho $y'' = 0 \Leftrightarrow 6x = 0 \Leftrightarrow x = 0$. Thay vào hàm số: $y(0) = 1$.
- - Điểm uốn $I_2(0; 1)$ chính là tâm đối xứng của đồ thị hàm số bậc ba.
- **Kết luận:** Tâm đối xứng của hai đồ thị lần lượt là $I_1(1; 2)$ và $I_2(0; 1)$.

#### Bài 4.4 [Mức 1: Nhận biết]
- **Đề bài:** Cho đồ thị hàm số bậc ba $y = ax^3 + bx^2 + cx + d$ ($a \ne 0$) có nhánh ngoài cùng bên phải đi lên, cắt trục tung tại điểm có tung độ âm, đạt cực trị tại $x = 0$ và $x = 2$. Hãy xác định dấu của hệ số $a$ và $d$.
- **Phương pháp & Gợi ý giải:** Nhánh phải đi lên $\Rightarrow a > 0$; cắt trục tung tại $(0; d) \Rightarrow$ dấu của $d$.
- **Lời giải chi tiết từng bước:**
- **Xác định dấu của $a$:** Khi $x \to +\infty$, nhánh ngoài cùng bên phải của đồ thị hướng đi lên phía trên, do đó $\lim_{x \to +\infty} y = +\infty \Rightarrow a > 0$.
- **Xác định dấu của $d$:** Giao điểm của đồ thị với trục tung $Oy$ (ứng với $x = 0$) có tọa độ $(0; d)$. Đề bài cho giao điểm có tung độ âm nên $d < 0$.
- **Kết luận:** $a > 0$ và $d < 0$.

#### Bài 4.5 [Mức 2: Thông hiểu]
- **Đề bài:** Khảo sát sự biến thiên và vẽ đồ thị của hàm số phân thức bậc hai trên bậc nhất $y = \dfrac{x^2 - x + 1}{x - 1}$.
- **Phương pháp & Gợi ý giải:** Viết $y = x + \dfrac{1}{x - 1}$, tìm TCĐ $x = 1$, TCX $y = x$, đạo hàm $y' = 1 - \dfrac{1}{(x-1)^2} = \dfrac{x^2 - 2x}{(x-1)^2}$.
- **Lời giải chi tiết từng bước:**
- **1. TXĐ:** $D = \mathbb{R} \setminus \{1\}$.
- **2. Sự biến thiên:**
- - Tiệm cận: $\lim_{x \to 1^+} y = +\infty, \lim_{x \to 1^-} y = -\infty \Rightarrow$ TCĐ $x = 1$. Ta có $y = x + \dfrac{1}{x - 1} \Rightarrow$ TCX $y = x$.
- - Đạo hàm: $y' = \dfrac{x^2 - 2x}{(x - 1)^2} = 0 \Leftrightarrow x = 0$ hoặc $x = 2$.
- - BBT: Hàm số đồng biến trên $(-\infty; 0)$ và $(2; +\infty)$; nghịch biến trên $(0; 1)$ và $(1; 2)$. Cực đại tại $x = 0, y_{CĐ} = -1$; cực tiểu tại $x = 2, y_{CT} = 3$.
- **3. Đồ thị:** Giao $Oy$ tại $(0; -1)$, không cắt $Ox$ (vì $x^2 - x + 1 > 0$). Tâm đối xứng $I(1; 1)$ là giao điểm của TCĐ và TCX.

#### Bài 4.6 [Mức 2: Thông hiểu]
- **Đề bài:** Viết phương trình tiếp tuyến của đồ thị hàm số $y = \dfrac{2x + 1}{x - 1}$ tại điểm có hoành độ $x_0 = 2$.
- **Phương pháp & Gợi ý giải:** Phương trình tiếp tuyến tại $M(x_0; y_0)$ là $y = y'(x_0)(x - x_0) + y_0$.
- **Lời giải chi tiết từng bước:**
- Tọa độ tiếp điểm: Hoành độ $x_0 = 2 \Rightarrow$ tung độ tiếp điểm $y_0 = y(2) = \dfrac{2(2) + 1}{2 - 1} = 5 \Rightarrow M(2; 5)$.
- Hệ số góc tiếp tuyến: $y' = \dfrac{2(-1) - 1(1)}{(x - 1)^2} = \dfrac{-3}{(x - 1)^2}$.
- Tại $x_0 = 2 \Rightarrow k = y'(2) = \dfrac{-3}{(2 - 1)^2} = -3$.
- Phương trình tiếp tuyến: $y = k(x - x_0) + y_0 \Leftrightarrow y = -3(x - 2) + 5 \Leftrightarrow y = -3x + 11$.
- **Kết luận:** Phương trình tiếp tuyến cần tìm là $y = -3x + 11$.

#### Bài 4.7 [Mức 2: Thông hiểu]
- **Đề bài:** Dựa vào đồ thị hàm số $y = x^3 - 3x^2 + 2$, biện luận theo tham số thực $m$ số nghiệm thực của phương trình $x^3 - 3x^2 + 2 - m = 0$.
- **Phương pháp & Gợi ý giải:** Biến đổi phương trình về dạng tương giao $x^3 - 3x^2 + 2 = m$, so sánh đường thẳng nằm ngang $y = m$ với các giá trị cực trị $y_{CĐ} = 2, y_{CT} = -2$.
- **Lời giải chi tiết từng bước:**
- Phương trình tương đương: $x^3 - 3x^2 + 2 = m$.
- Số nghiệm thực của phương trình là số giao điểm của đồ thị hàm số $(C): y = x^3 - 3x^2 + 2$ và đường thẳng nằm ngang $d: y = m$ song song hoặc trùng với trục hoành.
- Từ đồ thị (hoặc BBT) của hàm số bậc ba có $y_{CĐ} = 2$ và $y_{CT} = -2$:
- - Nếu $m < -2$ hoặc $m > 2$: Đường thẳng $d$ cắt $(C)$ tại đúng $1$ điểm phân biệt $\Rightarrow$ phương trình có $1$ nghiệm thực duy nhất.
- - Nếu $m = -2$ hoặc $m = 2$: Đường thẳng $d$ tiếp xúc với $(C)$ tại một điểm cực trị và cắt tại 1 điểm khác $\Rightarrow$ phương trình có đúng $2$ nghiệm thực phân biệt.
- - Nếu $-2 < m < 2$: Đường thẳng $d$ cắt $(C)$ tại đúng $3$ điểm phân biệt $\Rightarrow$ phương trình có $3$ nghiệm thực phân biệt.

#### Bài 4.8 [Mức 3: Vận dụng]
- **Đề bài:** Cho hàm số $y = x^3 - 3x + 1$ có đồ thị $(C)$. Tìm tất cả các giá trị của tham số $m$ để đường thẳng $d: y = mx + 1$ cắt đồ thị $(C)$ tại 3 điểm phân biệt.
- **Phương pháp & Gợi ý giải:** Lập phương trình hoành độ giao điểm, phân tích nhân tử đưa về $(x)(x^2 - m - 3) = 0$.
- **Lời giải chi tiết từng bước:**
- Phương trình hoành độ giao điểm của $(C)$ và $d$:
- $x^3 - 3x + 1 = mx + 1 \Leftrightarrow x^3 - (m + 3)x = 0 \Leftrightarrow x(x^2 - m - 3) = 0 \Leftrightarrow \begin{bmatrix} x = 0 \\ x^2 = m + 3 \end{bmatrix}$.
- Để đường thẳng $d$ cắt đồ thị $(C)$ tại 3 điểm phân biệt, phương trình bậc hai $x^2 = m + 3$ phải có 2 nghiệm phân biệt khác $0$.
- Điều này xảy ra khi và chỉ khi: $\begin{cases} m + 3 > 0 \\ m + 3 \ne 0 \end{cases} \Leftrightarrow m > -3$.
- **Kết luận:** $m > -3$ (hay $m \in (-3; +\infty)$).

#### Bài 4.9 [Mức 3: Vận dụng]
- **Đề bài:** Từ đồ thị hàm số $y = f(x) = \dfrac{2x - 1}{x + 1}$, hãy nêu các bước dựng đồ thị hàm số $y = |f(x)| = \left|\dfrac{2x - 1}{x + 1}\right|$ và tìm tất cả các giá trị của tham số $m$ để phương trình $|f(x)| = m$ có đúng 2 nghiệm thực phân biệt.
- **Phương pháp & Gợi ý giải:** Giữ nguyên phần đồ thị phía trên trục hoành, lấy đối xứng phần phía dưới qua $Ox$ rồi xóa phần dưới. Đường tiệm cận ngang mới là $y = 2$.
- **Lời giải chi tiết từng bước:**
- **Cách dựng đồ thị $y = |f(x)|$:**
- 1) Giữ nguyên phần đồ thị $y = f(x)$ nằm phía trên trục hoành $Ox$ (ứng với $f(x) \ge 0$).
- 2) Lấy đối xứng phần đồ thị $y = f(x)$ nằm phía dưới trục hoành $Ox$ qua trục $Ox$.
- 3) Xóa bỏ phần đồ thị phía dưới trục $Ox$. Khi đó tiệm cận ngang $y = 2$ vẫn giữ nguyên, đồ thị chạm trục hoành tại điểm $x = 1/2$.
- **Biện luận số nghiệm của $|f(x)| = m$:**
- - Nếu $m < 0$: Không có nghiệm thực.
- - Nếu $m = 0$: Có đúng 1 nghiệm $x = 1/2$.
- - Nếu $0 < m < 2$: Đường thẳng $y = m$ cắt 2 nhánh của đồ thị tại 2 điểm phân biệt $\Rightarrow$ có đúng 2 nghiệm phân biệt.
- - Nếu $m = 2$: Tiệm cận ngang, đường thẳng cắt 1 nhánh tại 1 điểm $\Rightarrow$ có 1 nghiệm.
- - Nếu $m > 2$: Cắt 2 nhánh tại 2 điểm phân biệt $\Rightarrow$ có 2 nghiệm phân biệt.
- **Kết luận:** Phương trình có đúng 2 nghiệm phân biệt khi $0 < m < 2$ hoặc $m > 2$.

#### Bài 4.10 [Mức 3: Vận dụng]
- **Đề bài:** Viết phương trình tiếp tuyến của đồ thị hàm số $y = \dfrac{x + 2}{x - 1}$ biết tiếp tuyến song song với đường thẳng $d: y = -3x + 4$.
- **Phương pháp & Gợi ý giải:** Tiếp tuyến song song với $d \Rightarrow$ hệ số góc $k = y'(x_0) = -3$. Giải tìm $x_0$, viết PTTT và loại trường hợp trùng với $d$.
- **Lời giải chi tiết từng bước:**
- Tập xác định: $D = \mathbb{R} \setminus \{1\}$. Đạo hàm $y' = \dfrac{1(-1) - 2(1)}{(x - 1)^2} = \dfrac{-3}{(x - 1)^2}$.
- Vì tiếp tuyến song song với $d: y = -3x + 4$ nên hệ số góc của tiếp tuyến là $k = -3$.
- Ta có phương trình: $\dfrac{-3}{(x_0 - 1)^2} = -3 \Leftrightarrow (x_0 - 1)^2 = 1 \Leftrightarrow \begin{bmatrix} x_0 - 1 = 1 \\ x_0 - 1 = -1 \end{bmatrix} \Leftrightarrow \begin{bmatrix} x_0 = 2 \\ x_0 = 0 \end{bmatrix}$.
- **Trường hợp 1 ($x_0 = 2$):** $y_0 = y(2) = \dfrac{2 + 2}{2 - 1} = 4$.
- Phương trình tiếp tuyến: $y = -3(x - 2) + 4 \Leftrightarrow y = -3x + 10$ (thỏa mãn vì khác $+4$).
- **Trường hợp 2 ($x_0 = 0$):** $y_0 = y(0) = \dfrac{0 + 2}{0 - 1} = -2$.
- Phương trình tiếp tuyến: $y = -3(x - 0) - 2 \Leftrightarrow y = -3x - 2$ (thỏa mãn vì khác $+4$).
- **Kết luận:** Có hai phương trình tiếp tuyến thỏa mãn là $y = -3x + 10$ và $y = -3x - 2$.

---

### 5. Dạng 5 (SGK Toán 12 KNTT): Ứng dụng đạo hàm giải quyết vấn đề thực tiễn — 10 Bài tự luận phân tầng
#### Bài 5.1 [Mức 1: Nhận biết]
- **Đề bài:** Một vật chuyển động thẳng có phương trình quãng đường $s(t) = t^3 - 6t^2 + 9t + 5$ ($t$ tính bằng giây, $s$ tính bằng mét). Tính vận tốc tức thời của vật tại thời điểm $t = 2\text{ s}$ và tìm các thời điểm mà vật dừng lại tức thời.
- **Phương pháp & Gợi ý giải:** Vận tốc tức thời là đạo hàm của quãng đường theo thời gian: $v(t) = s'(t)$. Vật dừng lại khi $v(t) = 0$.
- **Lời giải chi tiết từng bước:**
- **Phương trình vận tốc:** $v(t) = s'(t) = 3t^2 - 12t + 9$ (m/s).
- **Vận tốc tại thời điểm $t = 2\text{ s}$ là:**
- $v(2) = 3(2)^2 - 12(2) + 9 = 12 - 24 + 9 = -3\text{ m/s}$ (vật đang chuyển động ngược chiều dương với tốc độ $3\text{ m/s}$).
- **Thời điểm vật dừng lại tức thời:**
- Vật dừng lại khi $v(t) = 0 \Leftrightarrow 3t^2 - 12t + 9 = 0 \Leftrightarrow 3(t - 1)(t - 3) = 0 \Leftrightarrow t = 1\text{ s}$ hoặc $t = 3\text{ s}$.
- **Kết luận:** $v(2) = -3\text{ m/s}$; vật dừng lại tức thời tại $t = 1\text{ s}$ và $t = 3\text{ s}$.

#### Bài 5.2 [Mức 1: Nhận biết]
- **Đề bài:** Giả sử số lượng vi khuẩn trong một mẻ cấy thí nghiệm sau $t$ giờ được mô hình hóa bởi hàm số $N(t) = 1000 + 30t^2 - t^3$ ($0 \le t \le 20$). Tính tốc độ tăng trưởng tức thời của quần thể vi khuẩn tại thời điểm $t = 5\text{ giờ}$.
- **Phương pháp & Gợi ý giải:** Tốc độ tăng trưởng tức thời của quần thể vi khuẩn là đạo hàm bậc nhất $N'(t)$.
- **Lời giải chi tiết từng bước:**
- Tốc độ tăng trưởng tức thời của quần thể vi khuẩn tại thời điểm $t$ là:
- $N'(t) = (1000 + 30t^2 - t^3)' = 60t - 3t^2$ (cá thể/giờ).
- Tại thời điểm $t = 5\text{ giờ}$, tốc độ tăng trưởng tức thời là:
- $N'(5) = 60(5) - 3(5)^2 = 300 - 75 = 225$ (vi khuẩn/giờ).
- **Kết luận:** Tốc độ tăng trưởng tại thời điểm $t = 5\text{ giờ}$ là $225$ vi khuẩn/giờ.

#### Bài 5.3 [Mức 1: Nhận biết]
- **Đề bài:** Một doanh nghiệp sản xuất một loại sản phẩm với hàm tổng chi phí $C(x) = x^3 - 10x^2 + 50x + 100$ (nghìn đồng), trong đó $x$ là số lượng sản phẩm ($x > 0$). Xác định hàm chi phí biên $C'(x)$ và tính chi phí biên khi sản xuất đơn vị sản phẩm thứ $10$.
- **Phương pháp & Gợi ý giải:** Chi phí biên là đạo hàm của hàm tổng chi phí: $MC(x) = C'(x)$.
- **Lời giải chi tiết từng bước:**
- **Hàm chi phí biên:** $C'(x) = 3x^2 - 20x + 50$ (nghìn đồng/sản phẩm).
- **Chi phí biên tại $x = 10$:**
- $C'(10) = 3(10)^2 - 20(10) + 50 = 300 - 200 + 50 = 150$ (nghìn đồng).
- **Ý nghĩa thực tiễn:** Để sản xuất thêm sản phẩm thứ $11$ từ mức sản lượng $10$ sản phẩm, doanh nghiệp phải chi thêm xấp xỉ $150$ nghìn đồng.

#### Bài 5.4 [Mức 1: Nhận biết]
- **Đề bài:** Từ một tấm tôn hình vuông cạnh $60\text{ cm}$, người ta cắt bỏ bốn góc bốn hình vuông nhỏ bằng nhau có cạnh $x\text{ cm}$ rồi gập lại tạo thành một cái hộp không nắp. Hãy lập công thức tính thể tích $V(x)$ của chiếc hộp theo $x$ và tìm tập xác định của biến số $x$.
- **Phương pháp & Gợi ý giải:** Đáy hộp là hình vuông cạnh $60 - 2x$, chiều cao hộp là $x$. Thể tích $V = S_{đáy} \cdot h$.
- **Lời giải chi tiết từng bước:**
- Khi cắt bỏ 4 hình vuông cạnh $x$ ở 4 góc và gập lên:
- - Chiều cao của chiếc hộp là $h = x$ (cm).
- - Đáy của chiếc hộp là hình vuông có độ dài cạnh là $60 - 2x$ (cm).
- Điều kiện của $x$: Vì cạnh của hình vuông bị cắt bỏ và cạnh đáy phải dương nên $\begin{cases} x > 0 \\ 60 - 2x > 0 \end{cases} \Leftrightarrow 0 < x < 30$.
- Diện tích đáy hộp: $S(x) = (60 - 2x)^2\text{ cm}^2$.
- Thể tích của chiếc hộp là:
- $V(x) = x(60 - 2x)^2 = x(3600 - 240x + 4x^2) = 4x^3 - 240x^2 + 3600x\text{ (cm}^3)$.
- **Kết luận:** $V(x) = x(60 - 2x)^2\text{ cm}^3$ với tập xác định là khoảng $(0; 30)$.

#### Bài 5.5 [Mức 2: Thông hiểu]
- **Đề bài:** Với tấm tôn hình vuông cạnh $60\text{ cm}$ ở Bài 5.4, hãy tìm độ dài cạnh $x$ của hình vuông bị cắt bỏ để chiếc hộp thu được có thể tích lớn nhất và tính giá trị thể tích lớn nhất đó.
- **Phương pháp & Gợi ý giải:** Khảo sát hàm số $V(x) = 4x^3 - 240x^2 + 3600x$ trên khoảng $(0; 30)$, giải phương trình $V'(x) = 0$.
- **Lời giải chi tiết từng bước:**
- Xét hàm số $V(x) = 4x^3 - 240x^2 + 3600x$ trên khoảng $(0; 30)$.
- Đạo hàm: $V'(x) = 12x^2 - 480x + 3600 = 12(x^2 - 40x + 300)$.
- Cho $V'(x) = 0 \Leftrightarrow x^2 - 40x + 300 = 0 \Leftrightarrow x = 10$ hoặc $x = 30$.
- So sánh với điều kiện $0 < x < 30$, ta nhận $x = 10\text{ cm}$ (loại $x = 30$).
- Lập bảng biến thiên trên khoảng $(0; 30)$:
- - Với $0 < x < 10$: $V'(x) > 0$ (hàm đồng biến).
- - Với $10 < x < 30$: $V'(x) < 0$ (hàm nghịch biến).
- Do đó hàm số đạt cực đại tại $x = 10\text{ cm}$.
- Giá trị thể tích lớn nhất là:
- $V_{\max} = V(10) = 10(60 - 2\cdot 10)^2 = 10 \cdot 40^2 = 16000\text{ cm}^3 = 16\text{ dm}^3$ (lít).
- **Kết luận:** Để thể tích hộp lớn nhất, người thợ cần cắt hình vuông cạnh $x = 10\text{ cm}$; thể tích lớn nhất là $16000\text{ cm}^3$.

#### Bài 5.6 [Mức 2: Thông hiểu]
- **Đề bài:** Một công ty ước tính hàm cầu của một mặt hàng là $p(x) = 120 - 2x$ (nghìn đồng/sản phẩm), trong đó $x$ là số lượng sản phẩm tiêu thụ ($0 < x < 60$). Biết tổng chi phí để sản xuất $x$ sản phẩm là $C(x) = 20x + 300$ (nghìn đồng). Tìm mức sản lượng $x$ để công ty đạt lợi nhuận lớn nhất và tính lợi nhuận lớn nhất đó.
- **Phương pháp & Gợi ý giải:** Doanh thu $R(x) = x \cdot p(x)$. Lợi nhuận $L(x) = R(x) - C(x)$. Tìm cực đại của hàm bậc hai $L(x)$.
- **Lời giải chi tiết từng bước:**
- **Hàm tổng doanh thu:** $R(x) = x \cdot p(x) = x(120 - 2x) = 120x - 2x^2$ (nghìn đồng).
- **Hàm lợi nhuận:**
- $L(x) = R(x) - C(x) = (120x - 2x^2) - (20x + 300) = -2x^2 + 100x - 300$ (nghìn đồng) với $0 < x < 60$.
- **Tìm cực đại lợi nhuận:**
- Đạo hàm: $L'(x) = -4x + 100 = 0 \Leftrightarrow x = 25$ (sản phẩm) (thỏa mãn $0 < x < 60$).
- Vì $L(x)$ là tam thức bậc hai có hệ số $a = -2 < 0$, nên $L(x)$ đạt giá trị lớn nhất tại đỉnh $x = 25$.
- **Giá trị lợi nhuận lớn nhất:**
- $L_{\max} = L(25) = -2(25)^2 + 100(25) - 300 = -1250 + 2500 - 300 = 950$ (nghìn đồng).
- **Kết luận:** Công ty cần sản xuất và tiêu thụ $25$ sản phẩm để đạt lợi nhuận lớn nhất là $950$ nghìn đồng.

#### Bài 5.7 [Mức 2: Thông hiểu]
- **Đề bài:** Nồng độ một loại thuốc trong máu của bệnh nhân sau $t$ giờ kể từ khi tiêm được tính bởi công thức $C(t) = \dfrac{0{,}4t}{t^2 + 4}$ (mg/ml) với $t \ge 0$. Hỏi sau bao lâu kể từ lúc tiêm thì nồng độ thuốc trong máu đạt mức cao nhất và nồng độ cực đại đó là bao nhiêu?
- **Phương pháp & Gợi ý giải:** Khảo sát hàm $C(t)$ trên nửa khoảng $[0; +\infty)$, tính đạo hàm thương và lập BBT.
- **Lời giải chi tiết từng bước:**
- Xét hàm số $C(t) = \dfrac{0{,}4t}{t^2 + 4}$ trên $[0; +\infty)$.
- Đạo hàm: $C'(t) = \dfrac{0{,}4(t^2 + 4) - 0{,}4t(2t)}{(t^2 + 4)^2} = \dfrac{0{,}4(4 - t^2)}{(t^2 + 4)^2}$.
- Cho $C'(t) = 0 \Leftrightarrow 4 - t^2 = 0 \Leftrightarrow t = 2$ (do $t \ge 0$).
- Bảng biến thiên:
- - Với $0 \le t < 2$: $C'(t) > 0$ (nồng độ tăng).
- - Với $t > 2$: $C'(t) < 0$ (nồng độ giảm dần).
- Do đó $C(t)$ đạt giá trị lớn nhất tại $t = 2\text{ giờ}$.
- Nồng độ lớn nhất trong máu là: $C_{\max} = C(2) = \dfrac{0{,}4(2)}{2^2 + 4} = \dfrac{0{,}8}{8} = 0{,}1\text{ mg/ml}$.
- **Kết luận:** Sau $2$ giờ tiêm, nồng độ thuốc đạt mức cao nhất là $0{,}1\text{ mg/ml}$.

#### Bài 5.8 [Mức 3: Vận dụng]
- **Đề bài:** Một công ty cần thiết kế một bể chứa nước bằng thép hình trụ hở nắp có thể tích $V = 64\pi\text{ m}^3$. Hãy tìm bán kính đáy $R$ và chiều cao $h$ của bể để diện tích thép dùng làm bể (gồm một đáy và diện tích xung quanh) là nhỏ nhất nhằm tiết kiệm chi phí vật liệu nhất.
- **Phương pháp & Gợi ý giải:** Biểu diễn $h = \dfrac{V}{\pi R^2}$, lập hàm diện tích $S(R) = \pi R^2 + 2\pi R h = \pi R^2 + \dfrac{128\pi}{R}$, tìm cực tiểu của $S(R)$.
- **Lời giải chi tiết từng bước:**
- Thể tích bể hình trụ: $V = \pi R^2 h = 64\pi \Rightarrow h = \dfrac{64}{R^2}$ ($R > 0$).
- Diện tích thép dùng làm bể (gồm diện tích một đáy tròn và diện tích xung quanh):
- $S(R) = \pi R^2 + 2\pi R h = \pi R^2 + 2\pi R \cdot \dfrac{64}{R^2} = \pi\left(R^2 + \dfrac{128}{R}\right)$ ($R > 0$).
- Đạo hàm theo biến $R$:
- $S'(R) = \pi\left(2R - \dfrac{128}{R^2}\right) = \pi \cdot \dfrac{2R^3 - 128}{R^2}$.
- Cho $S'(R) = 0 \Leftrightarrow 2R^3 - 128 = 0 \Leftrightarrow R^3 = 64 \Leftrightarrow R = 4\text{ m}$.
- Lập BBT trên khoảng $(0; +\infty)$: Hàm số giảm trên $(0; 4)$ và tăng trên $(4; +\infty)$, do đó đạt cực tiểu tại $R = 4\text{ m}$.
- Chiều cao tương ứng: $h = \dfrac{64}{4^2} = 4\text{ m}$.
- Diện tích thép tối thiểu là: $S_{\min} = \pi(4^2 + 2\cdot 4 \cdot 4) = 48\pi\text{ m}^2 \approx 150{,}8\text{ m}^2$.
- **Kết luận:** Bán kính đáy tối ưu là $R = 4\text{ m}$ và chiều cao $h = 4\text{ m}$ (chiều cao bằng đúng bán kính đáy).

#### Bài 5.9 [Mức 3: Vận dụng]
- **Đề bài:** Một người chèo thuyền xuất phát từ điểm $A$ trên bờ biển muốn đến hòn đảo $B$ nằm cách bờ biển $6\text{ km}$. Điểm chiếu vuông góc của $B$ lên bờ biển là $C$, khoảng cách $AC = 8\text{ km}$. Người đó chèo thuyền dọc bờ biển từ $A$ đến điểm $M$ với vận tốc $5\text{ km/h}$, sau đó chèo thuyền từ $M$ thẳng đến đảo $B$ với vận tốc $3\text{ km/h}$. Hỏi điểm $M$ phải cách $C$ bao nhiêu km để thời gian di chuyển từ $A$ đến $B$ là ít nhất?
- **Phương pháp & Gợi ý giải:** Đặt khoảng cách $MC = x$ ($0 \le x \le 8$), quãng đường trên bờ là $AM = 8 - x$, quãng đường dưới nước là $MB = \sqrt{x^2 + 6^2}$. Lập hàm thời gian $T(x) = \dfrac{8-x}{5} + \dfrac{\sqrt{x^2+36}}{3}$.
- **Lời giải chi tiết từng bước:**
- Đặt khoảng cách $MC = x$ ($0 \le x \le 8$, đơn vị km).
- - Đoạn đường di chuyển dọc bờ biển: $AM = AC - MC = 8 - x$ (km).
- - Thời gian chèo dọc bờ biển: $t_1 = \dfrac{8 - x}{5}$ (giờ).
- - Đoạn đường chèo trên biển từ $M$ đến $B$: $MB = \sqrt{MC^2 + BC^2} = \sqrt{x^2 + 6^2} = \sqrt{x^2 + 36}$ (km).
- - Thời gian chèo trên biển: $t_2 = \dfrac{\sqrt{x^2 + 36}}{3}$ (giờ).
- Tổng thời gian di chuyển từ $A$ đến $B$ là hàm số:
- $T(x) = \dfrac{8 - x}{5} + \dfrac{\sqrt{x^2 + 36}}{3}$ ($0 \le x \le 8$).
- Đạo hàm: $T'(x) = -\dfrac{1}{5} + \dfrac{x}{3\sqrt{x^2 + 36}}$.
- Cho $T'(x) = 0 \Leftrightarrow \dfrac{x}{3\sqrt{x^2 + 36}} = \dfrac{1}{5} \Leftrightarrow 5x = 3\sqrt{x^2 + 36}$.
- Bình phương hai vế (vì $x \ge 0$): $25x^2 = 9(x^2 + 36) \Leftrightarrow 16x^2 = 324 \Leftrightarrow x^2 = \dfrac{324}{16} = \dfrac{81}{4} \Rightarrow x = \dfrac{9}{2} = 4{,}5\text{ km}$.
- Vì $4{,}5 \in [0; 8]$, tính các giá trị kiểm tra:
- $T(0) = \dfrac{8}{5} + \dfrac{6}{3} = 3{,}6\text{ giờ}$.
- $T(4{,}5) = \dfrac{8 - 4{,}5}{5} + \dfrac{\sqrt{4{,}5^2 + 36}}{3} = 0{,}7 + \dfrac{7{,}5}{3} = 0{,}7 + 2{,}5 = 3{,}2\text{ giờ}$.
- $T(8) = 0 + \dfrac{\sqrt{64 + 36}}{3} = \dfrac{10}{3} \approx 3{,}33\text{ giờ}$.
- Do $3{,}2 < 3{,}33 < 3{,}6$, nên $T(x)$ đạt giá trị nhỏ nhất tại $x = 4{,}5\text{ km}$.
- **Kết luận:** Điểm $M$ cách $C$ một khoảng $4{,}5\text{ km}$ thì thời gian di chuyển là ít nhất ($3$ giờ $12$ phút).

#### Bài 5.10 [Mức 3: Vận dụng]
- **Đề bài:** Một khách sạn có $100$ phòng. Nếu giá thuê mỗi phòng là $400.000$ đồng/ngày thì tất cả các phòng đều được thuê hết. Cứ mỗi lần khách sạn tăng giá phòng thêm $20.000$ đồng/ngày thì sẽ có thêm $2$ phòng bị bỏ trống. Biết chi phí dọn dẹp vệ sinh cho mỗi phòng có khách thuê là $40.000$ đồng/ngày. Hỏi khách sạn nên ấn định giá thuê phòng là bao nhiêu để lợi nhuận thu được trong một ngày là lớn nhất?
- **Phương pháp & Gợi ý giải:** Gọi $x$ là số lần tăng giá $20.000$ đồng ($x \ge 0$). Giá thuê phòng mới là $400 + 20x$, số phòng thuê là $100 - 2x$. Lợi nhuận mỗi phòng là giá thuê trừ chi phí $40$ nghìn.
- **Lời giải chi tiết từng bước:**
- Đơn vị tính: Nghìn đồng.
- - Giá thuê ban đầu: $400$ nghìn đồng/phòng. Chi phí dịch vụ: $40$ nghìn đồng/phòng có khách.
- - Lợi nhuận ban đầu trên mỗi phòng có khách: $400 - 40 = 360$ nghìn đồng.
- Gọi $x$ là số lần tăng giá thêm $20$ nghìn đồng ($x \ge 0$, $x \in \mathbb{R}$).
- - Giá thuê phòng sau khi tăng là: $400 + 20x$ (nghìn đồng/phòng).
- - Số phòng có khách thuê giảm còn: $100 - 2x$ (phòng) (điều kiện: $0 \le x < 50$).
- - Lợi nhuận thu được trên một phòng có khách thuê là: $(400 + 20x) - 40 = 360 + 20x$ (nghìn đồng).
- Tổng lợi nhuận trong ngày của khách sạn là hàm số:
- $P(x) = (100 - 2x)(360 + 20x) = 2(50 - x) \cdot 20(18 + x) = 40(50 - x)(18 + x)$
- $P(x) = 40(-x^2 + 32x + 900)$ (nghìn đồng).
- Hàm số $P(x)$ là tam thức bậc hai có hệ số $a = -40 < 0$, nên đạt giá trị lớn nhất tại đỉnh của parabol:
- $x_0 = -\dfrac{b}{2a} = -\dfrac{32}{2(-1)} = 16$ lần tăng giá.
- Khi $x = 16$:
- - Mức giá thuê phòng tối ưu là: $400 + 20(16) = 400 + 320 = 720$ (nghìn đồng/phòng/ngày) = $720.000$ đồng/ngày.
- - Số phòng có khách thuê là: $100 - 2(16) = 68$ phòng.
- - Tổng lợi nhuận tối đa trong ngày là: $P(16) = 40(-16^2 + 32(16) + 900) = 40(256 + 900) = 46.240$ nghìn đồng = $46.240.000$ đồng.
- **Kết luận:** Khách sạn nên ấn định giá thuê là $720.000$ đồng/ngày để đạt lợi nhuận lớn nhất.

---

## HỆ THỐNG 5 ĐỀ KIỂM TRA THEO TỪNG BÀI HỌC — HỖ TRỢ 2 DẠNG ĐỀ DO GIÁO VIÊN LỰA CHỌN
**Môn: Toán 12 — Bộ sách: Kết nối tri thức với cuộc sống (KNTT) | Thang điểm: 10,0 điểm/đề**

### Hai hình thức bài kiểm tra do Giáo viên lựa chọn:
1. **Dạng 1 — Đề kiểm tra 4 phần (21 câu — Kết hợp Trắc nghiệm & Tự luận theo Công văn 7991):**
   - **Phần I (Trắc nghiệm 4 lựa chọn):** $12$ câu (Câu 1 $\rightarrow$ Câu 12) $\times 0{,}25\text{đ} = 3{,}0\text{ điểm}$.
   - **Phần II (Trắc nghiệm Đúng / Sai):** $02$ câu (Câu 13 $\rightarrow$ Câu 14, mỗi câu 4 ý a, b, c, d) $\times 1{,}0\text{đ} = 2{,}0\text{ điểm}$.
   - **Phần III (Trắc nghiệm Trả lời ngắn):** $04$ câu (Câu 15 $\rightarrow$ Câu 18) $\times 0{,}50\text{đ} = 2{,}0\text{ điểm}$.
   - **Phần IV (Tự luận):** $03$ câu (Câu 19 $\rightarrow$ Câu 21) $\times 1{,}0\text{đ} = 3{,}0\text{ điểm}$.
2. **Dạng 2 — Đề kiểm tra 3 phần (22 câu — 100% Trắc nghiệm cấu trúc mới):**
   - **Phần I (Trắc nghiệm 4 lựa chọn):** $12$ câu (Câu 1 $\rightarrow$ Câu 12) $\times 0{,}25\text{đ} = 3{,}0\text{ điểm}$.
   - **Phần II (Trắc nghiệm Đúng / Sai):** $04$ câu (Câu 13 $\rightarrow$ Câu 16, mỗi câu 4 ý a, b, c, d) $\times 1{,}0\text{đ} = 4{,}0\text{ điểm}$.
   - **Phần III (Trắc nghiệm Trả lời ngắn):** $06$ câu (Câu 17 $\rightarrow$ Câu 22) $\times 0{,}50\text{đ} = 3{,}0\text{ điểm}$.

---

### ĐỀ KIỂM TRA SỐ 1 — ĐỀ KIỂM TRA BÀI 1 (CHUẨN CÔNG VĂN 7991): TÍNH ĐƠN ĐIỆU VÀ CỰC TRỊ CỦA HÀM SỐ — SGK TOÁN 12 KNTT

#### PHẦN I. Câu trắc nghiệm nhiều phương án lựa chọn (12 câu — Dùng cho cả Dạng 1 & Dạng 2: 3,0 điểm)
- **Câu 1 [Biết]:** Cho hàm số $y = x^3 - 3x^2 + 2$. Hàm số nghịch biến trên khoảng nào dưới đây?
  - A. $(-\infty; 0)$
  - B. $(0; 2)$
  - C. $(2; +\infty)$
  - D. $(-1; 1)$
- **Câu 2 [Biết]:** Cho hàm số $y = \dfrac{x + 2}{x - 1}$. Mệnh đề nào dưới đây đúng?
  - A. Nghịch biến trên $\mathbb{R} \setminus \{1\}$
  - B. Nghịch biến trên từng khoảng $(-\infty; 1)$ và $(1; +\infty)$
  - C. Đồng biến trên từng khoảng $(-\infty; 1)$ và $(1; +\infty)$
  - D. Nghịch biến trên $(-\infty; 1) \cup (1; +\infty)$
- **Câu 3 [Biết]:** Điểm cực tiểu của hàm số $y = x^3 - 3x^2 + 2$ là:
  - A. $x = 2$
  - B. $x = 0$
  - C. $y = -2$
  - D. $M(2; -2)$
- **Câu 4 [Biết]:** Giá trị cực đại $y_{CĐ}$ của hàm số $y = x^3 - 3x + 2$ bằng:
  - A. $4$
  - B. $-1$
  - C. $0$
  - D. $2$
- **Câu 5 [Biết]:** Cho hàm số $y = f(x)$ có đạo hàm $f'(x) = x(x + 2)^2(x - 3)^3, \forall x \in \mathbb{R}$. Số điểm cực trị của hàm số là:
  - A. $3$
  - B. $2$
  - C. $1$
  - D. $4$
- **Câu 6 [Biết]:** Số điểm cực trị của hàm số phân thức $y = \dfrac{2x - 1}{x + 3}$ là:
  - A. $0$
  - B. $1$
  - C. $2$
  - D. $3$
- **Câu 7 [Biết]:** Hàm số nào dưới đây đồng biến trên toàn bộ tập số thực $\mathbb{R}$?
  - A. $y = x^3 + 3x - 1$
  - B. $y = x^3 - 3x + 1$
  - C. $y = \dfrac{x - 1}{x + 1}$
  - D. $y = -x^3 - 3x$
- **Câu 8 [Biết]:** Tọa độ điểm cực đại của đồ thị hàm số $y = -x^3 + 3x^2 + 1$ là:
  - A. $M(2; 5)$
  - B. $M(0; 1)$
  - C. $x = 2$
  - D. $M(2; 1)$
- **Câu 9 [Hiểu]:** Hàm số $y = x + \dfrac{4}{x}$ nghịch biến trên khoảng nào dưới đây?
  - A. $(0; 2)$
  - B. $(-2; 2)$
  - C. $(2; +\infty)$
  - D. $(-\infty; -2)$
- **Câu 10 [Hiểu]:** Tìm tất cả các giá trị thực của tham số $m$ để hàm số $y = \dfrac{mx - 4}{x - m}$ đồng biến trên từng khoảng xác định:
  - A. $-2 \le m \le 2$
  - B. $-2 < m < 2$
  - C. $m > 2$ hoặc $m < -2$
  - D. $m \ge 2$
- **Câu 11 [Hiểu]:** Hàm số $y = x^3 - 3mx^2 + 3(2m - 1)x + 1$ có hai điểm cực trị khi và chỉ khi:
  - A. $m \ne 1$
  - B. $m = 1$
  - C. $m > 1$
  - D. $\forall m \in \mathbb{R}$
- **Câu 12 [Vận dụng]:** Cho hàm số $y = f(x)$ có đạo hàm $f'(x) = x^2 - 2x, \forall x \in \mathbb{R}$. Hàm số $g(x) = f(x + 1)$ nghịch biến trên khoảng nào?
  - A. $(-1; 1)$
  - B. $(0; 2)$
  - C. $(1; 3)$
  - D. $(-\infty; -1)$

#### PHẦN II. Câu trắc nghiệm Đúng / Sai (Dạng 1 lấy 2 câu đầu = 2,0đ; Dạng 2 lấy đủ 4 câu = 4,0đ)
- **Câu Đ/S 1 (Dạng 1 & Dạng 2):** Cho hàm số bậc ba $y = f(x) = x^3 - 3x + 2$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đạo hàm của hàm số đã cho là $f'(x) = 3x^2 - 3$. *[Biết]*
  - b) Hàm số nghịch biến trên khoảng $(-1; 1)$. *[Biết]*
  - c) Giá trị cực tiểu của hàm số bằng $1$. *[Hiểu]*
  - d) Hàm số hợp $g(x) = f(2x - 1)$ nghịch biến trên khoảng $(0; 1)$. *[Vận dụng]*
- **Câu Đ/S 2 (Dạng 1 & Dạng 2):** Cho hàm số phân thức $y = f(x) = \dfrac{x^2 - 2x + 5}{x - 1}$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Tập xác định của hàm số là $D = \mathbb{R} \setminus \{1\}$. *[Biết]*
  - b) Đạo hàm của hàm số là $f'(x) = \dfrac{x^2 - 2x - 3}{(x - 1)^2}$. *[Biết]*
  - c) Hàm số đồng biến trên khoảng $(-1; 3)$. *[Hiểu]*
  - d) Tổng giá trị cực đại và giá trị cực tiểu của hàm số bằng $0$. *[Vận dụng]*
- **Câu Đ/S 3 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số bậc ba $y = f(x) = -x^3 + 3x^2 + 9x - 2$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đạo hàm của hàm số là $f'(x) = -3x^2 + 6x + 9$. *[Biết]*
  - b) Hàm số đồng biến trên khoảng $(-1; 3)$. *[Biết]*
  - c) Điểm cực đại của hàm số là $x = -1$. *[Hiểu]*
  - d) Đường thẳng đi qua hai điểm cực trị của đồ thị hàm số có phương trình là $y = 6x + 1$. *[Vận dụng]*
- **Câu Đ/S 4 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số $y = f(x)$ liên tục trên $\mathbb{R}$ và có đạo hàm $f'(x) = (x - 1)(x + 2)^2(x - 4)^3$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Phương trình $f'(x) = 0$ có $3$ nghiệm thực phân biệt là $x = 1, x = -2, x = 4$. *[Biết]*
  - b) Hàm số $y = f(x)$ đạt cực trị tại điểm $x = -2$. *[Biết]*
  - c) Hàm số $y = f(x)$ nghịch biến trên khoảng $(1; 4)$. *[Hiểu]*
  - d) Hàm số $y = f(x)$ có đúng $2$ điểm cực trị trên $\mathbb{R}$. *[Vận dụng]*

#### PHẦN III. Câu trắc nghiệm Trả lời ngắn (Dạng 1 lấy 4 câu đầu = 2,0đ; Dạng 2 lấy đủ 6 câu = 3,0đ)
- **Câu TLN 1 [Hiểu • Dạng 1 & Dạng 2]:** Có bao nhiêu giá trị nguyên của tham số $m$ để hàm số $y = \dfrac{1}{3}x^3 - mx^2 + 4x + 2$ đồng biến trên $\mathbb{R}$?
- **Câu TLN 2 [Hiểu • Dạng 1 & Dạng 2]:** Biết đồ thị hàm số $y = x^3 - 3x^2 + 2$ có hai điểm cực trị $A(0; 2)$ và $B(2; -2)$. Tính bình phương độ dài đoạn thẳng $AB$ (tức $AB^2$).
- **Câu TLN 3 [Vận dụng • Dạng 1 & Dạng 2]:** Tìm giá trị thực của tham số $m$ để hàm số $y = \dfrac{1}{3}x^3 - mx^2 + (m^2 - 4)x + 1$ đạt cực đại tại $x = 1$.
- **Câu TLN 4 [Vận dụng • Dạng 1 & Dạng 2]:** Cho hàm số $y = f(x)$ có đạo hàm $f'(x) = x(x - 2), \forall x \in \mathbb{R}$. Hàm số $g(x) = f(x^2)$ có bao nhiêu điểm cực trị?
- **Câu TLN 5 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Có bao nhiêu giá trị nguyên của tham số $m \in [-5; 5]$ để hàm số $y = \dfrac{x + m}{x + 2}$ đồng biến trên từng khoảng xác định?
- **Câu TLN 6 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Biết hàm số $y = x^3 - 6x^2 + 9x - 1$ có hai điểm cực trị là $x_1$ và $x_2$. Tính giá trị biểu thức $P = x_1^2 + x_2^2$.

#### PHẦN IV. Tự luận (Dành cho Dạng 1 gồm 4 phần 21 câu: 3 câu × 1,0 điểm = 3,0 điểm)
- **Câu 19 [1,0đ • Tự luận 1 • Khảo sát tính đơn điệu & cực trị hàm bậc ba]:** Câu 19 (1,0 điểm): Tìm các khoảng đơn điệu và cực trị của hàm số $y = x^3 - 3x^2 + 1$.
- **Câu 20 [1,0đ • Tự luận 2 • Đơn điệu & cực trị hàm phân thức bậc 2/1]:** Câu 20 (1,0 điểm): Tìm các khoảng đồng biến, nghịch biến và các điểm cực trị của hàm số $y = \dfrac{x^2 - 2x + 5}{x - 1}$.
- **Câu 21 [1,0đ • Tự luận 3 • Định tham số m để hàm số đơn điệu trên khoảng]:** Câu 21 (1,0 điểm): Tìm tất cả các giá trị của tham số $m$ để hàm số $y = x^3 - 3mx^2 + 3(m^2 - 1)x + 2$ nghịch biến trên khoảng $(0; 1)$.

> **Đáp án & Hướng dẫn chấm Đề 1 (Bài 1):**
> - **Phần I (12 câu TN):** 1.B | 2.B | 3.A | 4.A | 5.B | 6.A | 7.A | 8.A | 9.A | 10.B | 11.A | 12.A.
> - **Phần II (4 câu Đ/S):** **Câu Đ/S 1:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 2:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 3:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 4:** a) Đ, b) S, c) Đ, d) Đ.
> - **Phần III (6 câu TLN):** TLN 1: `5` | TLN 2: `20` | TLN 3: `3` | TLN 4: `3` | TLN 5: `7` | TLN 6: `10`.
> - **Phần IV — Câu 19 [1,0đ • Tự luận 1 • Khảo sát tính đơn điệu & cực trị hàm bậc ba]:** TXĐ D = R. y' = 3x^2 - 6x = 0 <=> x = 0 hoặc x = 2. Hàm số ĐB trên (-vc; 0) và (2; +vc); NB trên (0; 2). Đạt CĐ tại x = 0, y_CD = 1; đạt CT tại x = 2, y_CT = -3. *(Rubric: TXĐ D = R & tính đúng y' = 3x^2 - 6x = 0 (0,25đ) • Lập bảng biến thiên đúng (0,25đ) • Kết luận đúng khoảng ĐB, NB và cực trị (0,5đ).)*
> - **Phần IV — Câu 20 [1,0đ • Tự luận 2 • Đơn điệu & cực trị hàm phân thức bậc 2/1]:** TXĐ D = R \ {1}. y' = (x^2 - 2x - 3)/(x - 1)^2 = 0 <=> x = -1 hoặc x = 3. Hàm số ĐB trên (-vc; -1) và (3; +vc); NB trên (-1; 1) và (1; 3). Đạt CĐ tại x = -1 (y_CD = -4), đạt CT tại x = 3 (y_CT = 4). *(Rubric: TXĐ D = R\{1} & tính y' = (x^2-2x-3)/(x-1)^2 (0,5đ) • Lập BBT & kết luận đúng khoảng đơn điệu, cực trị (0,5đ).)*
> - **Phần IV — Câu 21 [1,0đ • Tự luận 3 • Định tham số m để hàm số đơn điệu trên khoảng]:** Ta có y' = 3x^2 - 6mx + 3(m^2 - 1) = 3(x - m + 1)(x - m - 1). Hàm số nghịch biến trên (m - 1; m + 1). Để nghịch biến trên (0; 1) thì (0; 1) con (m - 1; m + 1) <=> m - 1 <= 0 và m + 1 >= 1 <=> 0 <= m <= 1. *(Rubric: Tính y' và tìm 2 nghiệm m - 1, m + 1 (0,5đ) • Lý luận (0; 1) chứa trong (m - 1; m + 1) giải ra 0 <= m <= 1 (0,5đ).)*

---

### ĐỀ KIỂM TRA SỐ 2 — ĐỀ KIỂM TRA BÀI 2 (CHUẨN CÔNG VĂN 7991): GIÁ TRỊ LỚN NHẤT VÀ GIÁ TRỊ NHỎ NHẤT CỦA HÀM SỐ — SGK TOÁN 12 KNTT

#### PHẦN I. Câu trắc nghiệm nhiều phương án lựa chọn (12 câu — Dùng cho cả Dạng 1 & Dạng 2: 3,0 điểm)
- **Câu 1 [Biết]:** Giá trị lớn nhất của hàm số $f(x) = x^3 - 3x + 2$ trên đoạn $[0; 2]$ bằng:
  - A. $2$
  - B. $4$
  - C. $0$
  - D. $1$
- **Câu 2 [Biết]:** Giá trị nhỏ nhất của hàm số $y = \dfrac{x - 1}{x + 1}$ trên đoạn $[0; 3]$ bằng:
  - A. $\dfrac{1}{2}$
  - B. $-1$
  - C. $0$
  - D. $1$
- **Câu 3 [Biết]:** Giá trị nhỏ nhất của hàm số $f(x) = x^3 - 3x^2 + 5$ trên đoạn $[0; 3]$ bằng:
  - A. $1$
  - B. $5$
  - C. $0$
  - D. $2$
- **Câu 4 [Biết]:** Giá trị lớn nhất của hàm số $y = \sqrt{9 - x^2}$ trên đoạn $[-3; 3]$ bằng:
  - A. $3$
  - B. $9$
  - C. $0$
  - D. $6$
- **Câu 5 [Biết]:** Cho hàm số $y = f(x)$ liên tục và nghịch biến trên đoạn $[1; 5]$. Giá trị lớn nhất của hàm số $f(x)$ trên đoạn $[1; 5]$ là:
  - A. $f(1)$
  - B. $f(5)$
  - C. $f(3)$
  - D. $0$
- **Câu 6 [Biết]:** Giá trị nhỏ nhất của hàm số $f(x) = x + \dfrac{9}{x}$ trên khoảng $(0; +\infty)$ đạt được tại điểm $x_0$ bằng:
  - A. $x_0 = 6$
  - B. $x_0 = 3$
  - C. $x_0 = 9$
  - D. $x_0 = 1$
- **Câu 7 [Biết]:** Giá trị lớn nhất của hàm số $y = \dfrac{2x + 1}{x - 1}$ trên đoạn $[2; 3]$ bằng:
  - A. $5$
  - B. $\dfrac{7}{2}$
  - C. $3$
  - D. $2$
- **Câu 8 [Biết]:** Giá trị nhỏ nhất của hàm số $y = e^x$ trên đoạn $[0; 2]$ bằng:
  - A. $1$
  - B. $e$
  - C. $e^2$
  - D. $0$
- **Câu 9 [Hiểu]:** Gọi $M, m$ lần lượt là GTLN và GTNN của hàm số $y = \dfrac{2x - 1}{x + 1}$ trên đoạn $[0; 2]$. Tổng $M + m$ bằng:
  - A. $0$
  - B. $2$
  - C. $1$
  - D. $-1$
- **Câu 10 [Hiểu]:** Giá trị lớn nhất của hàm số $y = x + \sqrt{4 - x^2}$ trên đoạn $[-2; 2]$ bằng:
  - A. $2\sqrt{2}$
  - B. $2$
  - C. $4$
  - D. $-2$
- **Câu 11 [Hiểu]:** Giá trị lớn nhất của hàm số $f(x) = x + \dfrac{4}{x}$ trên khoảng $(-\infty; 0)$ bằng:
  - A. $-4$
  - B. $4$
  - C. $-2$
  - D. $2$
- **Câu 12 [Vận dụng]:** Giá trị của tham số $m$ để hàm số $y = x^3 - 3x^2 + m$ có giá trị nhỏ nhất trên đoạn $[-1; 1]$ bằng $0$ là:
  - A. $m = 4$
  - B. $m = 2$
  - C. $m = 0$
  - D. $m = -4$

#### PHẦN II. Câu trắc nghiệm Đúng / Sai (Dạng 1 lấy 2 câu đầu = 2,0đ; Dạng 2 lấy đủ 4 câu = 4,0đ)
- **Câu Đ/S 1 (Dạng 1 & Dạng 2):** Cho hàm số $f(x) = x^3 - 3x^2 - 9x + 35$ xét trên đoạn $[-4; 4]$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đạo hàm của hàm số là $f'(x) = 3x^2 - 6x - 9$. *[Biết]*
  - b) Phương trình $f'(x) = 0$ có hai nghiệm thuộc $(-4; 4)$ là $x = -1$ và $x = 3$. *[Biết]*
  - c) Giá trị lớn nhất của hàm số trên đoạn $[-4; 4]$ bằng $15$. *[Hiểu]*
  - d) Tổng GTLN và GTNN của hàm số trên đoạn $[-4; 4]$ bằng $-1$. *[Vận dụng]*
- **Câu Đ/S 2 (Dạng 1 & Dạng 2):** Cho hàm số $g(x) = x + \dfrac{4}{x - 1}$ xét trên khoảng $(1; +\infty)$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đạo hàm của hàm số là $g'(x) = 1 - \dfrac{4}{(x - 1)^2}$. *[Biết]*
  - b) Trên khoảng $(1; +\infty)$, phương trình $g'(x) = 0$ có nghiệm duy nhất $x = 3$. *[Biết]*
  - c) Giá trị nhỏ nhất của hàm số $g(x)$ trên khoảng $(1; +\infty)$ bằng $3$. *[Hiểu]*
  - d) Trên đoạn $[2; 5]$, giá trị lớn nhất của hàm số $g(x)$ bằng $6$. *[Vận dụng]*
- **Câu Đ/S 3 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số phân thức $y = f(x) = \dfrac{2x + 1}{x - 2}$ xét trên đoạn $[3; 6]$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Hàm số liên tục trên đoạn $[3; 6]$. *[Biết]*
  - b) Đạo hàm $f'(x) = \dfrac{-5}{(x - 2)^2} < 0, \forall x \in [3; 6]$. *[Biết]*
  - c) Giá trị lớn nhất của hàm số trên đoạn $[3; 6]$ đạt tại $x = 6$. *[Hiểu]*
  - d) Hiệu giữa GTLN và GTNN của hàm số trên đoạn $[3; 6]$ bằng $\dfrac{15}{4}$. *[Vận dụng]*
- **Câu Đ/S 4 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số $y = f(x) = \sqrt{8 - x^2}$ xác định trên đoạn $[-2\sqrt{2}; 2\sqrt{2}]$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Tập xác định của hàm số là $D = [-2\sqrt{2}; 2\sqrt{2}]$. *[Biết]*
  - b) Đạo hàm $f'(x) = 0$ khi và chỉ khi $x = 0$. *[Biết]*
  - c) Giá trị nhỏ nhất của hàm số trên đoạn $[-2\sqrt{2}; 2\sqrt{2}]$ bằng $-2\sqrt{2}$. *[Hiểu]*
  - d) Giá trị lớn nhất của hàm số $g(x) = x + \sqrt{8 - x^2}$ trên đoạn $[-2\sqrt{2}; 2\sqrt{2}]$ bằng $4$. *[Vận dụng]*

#### PHẦN III. Câu trắc nghiệm Trả lời ngắn (Dạng 1 lấy 4 câu đầu = 2,0đ; Dạng 2 lấy đủ 6 câu = 3,0đ)
- **Câu TLN 1 [Hiểu • Dạng 1 & Dạng 2]:** Tìm giá trị nhỏ nhất của hàm số $f(x) = x + \dfrac{4}{x - 1}$ trên khoảng $(1; +\infty)$.
- **Câu TLN 2 [Hiểu • Dạng 1 & Dạng 2]:** Tìm giá trị thực của tham số $m$ để hàm số $y = \dfrac{x + m}{x - 1}$ thỏa mãn $\min_{[2; 4]} y = 3$.
- **Câu TLN 3 [Vận dụng • Dạng 1 & Dạng 2]:** Gọi $M, m$ lần lượt là GTLN và GTNN của hàm số $y = x^3 - 3x + 3$ trên đoạn $[0; 2]$. Tính tích $M \cdot m$.
- **Câu TLN 4 [Vận dụng • Dạng 1 & Dạng 2]:** Một hình chữ nhật có chu vi bằng $20\text{ cm}$. Diện tích lớn nhất của hình chữ nhật đó bằng bao nhiêu $\text{cm}^2$?
- **Câu TLN 5 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Tìm giá trị thực của tham số $m$ để hàm số $y = x^3 - 3x^2 + m$ có giá trị lớn nhất trên đoạn $[0; 3]$ bằng $8$.
- **Câu TLN 6 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Tìm giá trị nhỏ nhất của hàm số $y = x + \dfrac{16}{x + 1}$ trên khoảng $(-1; +\infty)$.

#### PHẦN IV. Tự luận (Dành cho Dạng 1 gồm 4 phần 21 câu: 3 câu × 1,0 điểm = 3,0 điểm)
- **Câu 19 [1,0đ • Tự luận 1 • Tìm GTLN và GTNN trên đoạn]:** Câu 19 (1,0 điểm): Tìm giá trị lớn nhất và giá trị nhỏ nhất của hàm số $f(x) = x^3 - 3x^2 - 9x + 5$ trên đoạn $[0; 4]$.
- **Câu 20 [1,0đ • Tự luận 2 • Tìm GTNN trên khoảng mở bằng BBT]:** Câu 20 (1,0 điểm): Lập bảng biến thiên và tìm giá trị nhỏ nhất của hàm số $g(x) = x + \dfrac{9}{x - 2}$ trên khoảng $(2; +\infty)$.
- **Câu 21 [1,0đ • Tự luận 3 • Định m để GTLN-GTNN hàm phân thức thỏa điều kiện]:** Câu 21 (1,0 điểm): Tìm các giá trị của tham số $m$ để hàm số $y = \dfrac{x - m^2}{x + 1}$ có giá trị nhỏ nhất trên đoạn $[0; 1]$ bằng $-4$.

> **Đáp án & Hướng dẫn chấm Đề 2 (Bài 2):**
> - **Phần I (12 câu TN):** 1.B | 2.B | 3.A | 4.A | 5.A | 6.B | 7.A | 8.A | 9.A | 10.A | 11.A | 12.A.
> - **Phần II (4 câu Đ/S):** **Câu Đ/S 1:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 2:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 3:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 4:** a) Đ, b) Đ, c) S, d) Đ.
> - **Phần III (6 câu TLN):** TLN 1: `5` | TLN 2: `5` | TLN 3: `5` | TLN 4: `25` | TLN 5: `8` | TLN 6: `7`.
> - **Phần IV — Câu 19 [1,0đ • Tự luận 1 • Tìm GTLN và GTNN trên đoạn]:** Hàm số liên tục trên [0; 4]. Ta có y' = 3x^2 - 6x - 9 = 0 <=> x = 3 thuộc (0; 4) (loại x = -1). Tính f(0) = 5, f(3) = -22, f(4) = -15. Vậy max f(x) = 5 tại x = 0 và min f(x) = -22 tại x = 3. *(Rubric: Giải f'(x)=0 lấy x=3 thuộc (0;4) (0,25đ) • Tính f(0)=5, f(3)=-22, f(4)=-15 (0,5đ) • Kết luận Max=5, Min=-22 (0,25đ).)*
> - **Phần IV — Câu 20 [1,0đ • Tự luận 2 • Tìm GTNN trên khoảng mở bằng BBT]:** Với x > 2, g'(x) = 1 - 9/(x - 2)^2 = 0 <=> x - 2 = 3 <=> x = 5 thuộc (2; +vc). Lập BBT trên (2; +vc) suy ra hàm số đạt GTNN tại x = 5 và min g(x) = g(5) = 5 + 9/3 = 8. *(Rubric: Tính g'(x) và tìm nghiệm x = 5 thuộc (2; +vc) (0,5đ) • Lập BBT và kết luận min g(x) = 8 tại x = 5 (0,5đ).)*
> - **Phần IV — Câu 21 [1,0đ • Tự luận 3 • Định m để GTLN-GTNN hàm phân thức thỏa điều kiện]:** Trên [0; 1], y' = (1 + m^2)/(x + 1)^2 > 0 với mọi m nên hàm số luôn đồng biến trên [0; 1]. Do đó min_[0;1] y = y(0) = -m^2. Theo đề -m^2 = -4 <=> m^2 = 4 <=> m = 2 hoặc m = -2. *(Rubric: Chỉ ra y' = (1 + m^2)/(x + 1)^2 > 0 nên hàm đồng biến trên [0;1] (0,5đ) • Suy ra min y = y(0) = -m^2 = -4 <=> m = +-2 (0,5đ).)*

---

### ĐỀ KIỂM TRA SỐ 3 — ĐỀ KIỂM TRA BÀI 3 (CHUẨN CÔNG VĂN 7991): ĐƯỜNG TIỆM CẬN CỦA ĐỒ THỊ HÀM SỐ — SGK TOÁN 12 KNTT

#### PHẦN I. Câu trắc nghiệm nhiều phương án lựa chọn (12 câu — Dùng cho cả Dạng 1 & Dạng 2: 3,0 điểm)
- **Câu 1 [Biết]:** Đường tiệm cận ngang của đồ thị hàm số $y = \dfrac{4x - 1}{x + 2}$ là:
  - A. $x = -2$
  - B. $y = 4$
  - C. $y = -2$
  - D. $y = -\dfrac{1}{2}$
- **Câu 2 [Biết]:** Đường tiệm cận đứng của đồ thị hàm số $y = \dfrac{2x + 1}{x - 3}$ là:
  - A. $y = 2$
  - B. $x = 3$
  - C. $x = -3$
  - D. $y = 3$
- **Câu 3 [Biết]:** Đường tiệm cận xiên của đồ thị hàm số $y = 2x - 3 + \dfrac{5}{x + 1}$ là:
  - A. $y = 2x + 3$
  - B. $y = 2x - 3$
  - C. $x = -1$
  - D. $y = 5$
- **Câu 4 [Biết]:** Tổng số đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{x + 1}{x^2 - 9}$ là:
  - A. $3$
  - B. $2$
  - C. $1$
  - D. $4$
- **Câu 5 [Biết]:** Đường tiệm cận ngang của đồ thị hàm số $y = \dfrac{5}{x - 2}$ là:
  - A. $y = 0$
  - B. $x = 2$
  - C. $y = 5$
  - D. $y = 2$
- **Câu 6 [Biết]:** Đồ thị của hàm số nào dưới đây không có đường tiệm cận đứng?
  - A. $y = \dfrac{2x + 1}{x^2 + 1}$
  - B. $y = \dfrac{1}{x - 1}$
  - C. $y = \dfrac{x}{x + 2}$
  - D. $y = \dfrac{x^2 + 1}{x}$
- **Câu 7 [Biết]:** Giao điểm $I$ của hai đường tiệm cận của đồ thị hàm số $y = \dfrac{3x - 1}{x - 2}$ có tọa độ là:
  - A. $I(2; 3)$
  - B. $I(3; 2)$
  - C. $I(-2; 3)$
  - D. $I(2; -1)$
- **Câu 8 [Biết]:** Cho hàm số $y = f(x)$ thỏa mãn $\lim_{x \to +\infty} f(x) = 2$ và $\lim_{x \to -\infty} f(x) = -2$. Số đường tiệm cận ngang của đồ thị hàm số là:
  - A. $2$
  - B. $1$
  - C. $0$
  - D. $3$
- **Câu 9 [Hiểu]:** Đường tiệm cận xiên của đồ thị hàm số $y = \dfrac{x^2 - 3x + 5}{x - 2}$ là:
  - A. $y = x - 1$
  - B. $y = x - 3$
  - C. $y = x + 1$
  - D. $y = x - 2$
- **Câu 10 [Hiểu]:** Số đường tiệm cận đứng của đồ thị hàm số $y = \dfrac{x - 2}{x^2 - 3x + 2}$ là:
  - A. $1$
  - B. $2$
  - C. $0$
  - D. $3$
- **Câu 11 [Hiểu]:** Tọa độ giao điểm $I$ của đường tiệm cận đứng và đường tiệm cận xiên của đồ thị hàm số $y = 2x - 1 + \dfrac{3}{x + 1}$ là:
  - A. $I(-1; -3)$
  - B. $I(1; 1)$
  - C. $I(-1; 3)$
  - D. $I(-1; -1)$
- **Câu 12 [Vận dụng]:** Hai đường tiệm cận của đồ thị hàm số $y = \dfrac{2x + 1}{x - 3}$ tạo với hai trục tọa độ $Ox, Oy$ một hình chữ nhật có diện tích bằng:
  - A. $6$
  - B. $3$
  - C. $2$
  - D. $5$

#### PHẦN II. Câu trắc nghiệm Đúng / Sai (Dạng 1 lấy 2 câu đầu = 2,0đ; Dạng 2 lấy đủ 4 câu = 4,0đ)
- **Câu Đ/S 1 (Dạng 1 & Dạng 2):** Cho hàm số $y = f(x) = \dfrac{2x^2 - 3x - 1}{x - 2}$ có đồ thị $(C)$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Tập xác định của hàm số là $D = \mathbb{R} \setminus \{2\}$. *[Biết]*
  - b) Đồ thị $(C)$ có đường tiệm cận ngang là $y = 2$. *[Biết]*
  - c) Đường thẳng $y = 2x - 1$ là đường tiệm cận xiên của đồ thị $(C)$. *[Hiểu]*
  - d) Giao điểm $I$ của tiệm cận đứng và tiệm cận xiên của $(C)$ có tọa độ là $I(2; 5)$. *[Vận dụng]*
- **Câu Đ/S 2 (Dạng 1 & Dạng 2):** Cho hàm số $y = g(x) = \dfrac{3x - 1}{x + 2}$ có đồ thị $(C')$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đường thẳng $x = -2$ là tiệm cận đứng của đồ thị $(C')$. *[Biết]*
  - b) Đường thẳng $y = 3$ là tiệm cận ngang của đồ thị $(C')$. *[Biết]*
  - c) Đồ thị $(C')$ có thêm một đường tiệm cận xiên là $y = 3x - 1$. *[Hiểu]*
  - d) Hình chữ nhật tạo bởi hai đường tiệm cận của $(C')$ và hai trục tọa độ có diện tích bằng $6$. *[Vận dụng]*
- **Câu Đ/S 3 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số $y = f(x) = \dfrac{x - 1}{x^2 - 4}$ có đồ thị $(C)$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Tập xác định của hàm số là $D = \mathbb{R} \setminus \{-2; 2\}$. *[Biết]*
  - b) Đường thẳng $y = 0$ là đường tiệm cận ngang của đồ thị $(C)$. *[Biết]*
  - c) Đồ thị $(C)$ chỉ có đúng $1$ đường tiệm cận đứng là $x = 2$. *[Hiểu]*
  - d) Tổng số đường tiệm cận đứng và tiệm cận ngang của đồ thị $(C)$ là $3$. *[Vận dụng]*
- **Câu Đ/S 4 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số phân thức $y = f(x) = \dfrac{x^2 + 2x + 3}{x + 1}$ có đồ thị $(C')$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đường thẳng $x = -1$ là tiệm cận đứng của đồ thị $(C')$. *[Biết]*
  - b) Ta có thể viết lại hàm số dưới dạng $y = x + 1 + \dfrac{2}{x + 1}$. *[Biết]*
  - c) Đường tiệm cận xiên của đồ thị $(C')$ đi qua gốc tọa độ $O(0; 0)$. *[Hiểu]*
  - d) Giao điểm hai đường tiệm cận của đồ thị $(C')$ là điểm $I(-1; 0)$. *[Vận dụng]*

#### PHẦN III. Câu trắc nghiệm Trả lời ngắn (Dạng 1 lấy 4 câu đầu = 2,0đ; Dạng 2 lấy đủ 6 câu = 3,0đ)
- **Câu TLN 1 [Hiểu • Dạng 1 & Dạng 2]:** Đồ thị hàm số $y = \dfrac{x - 2}{x^2 - 3x + 2}$ có bao nhiêu đường tiệm cận đứng?
- **Câu TLN 2 [Hiểu • Dạng 1 & Dạng 2]:** Biết đường tiệm cận xiên của đồ thị hàm số $y = \dfrac{2x^2 + 3x - 5}{x + 2}$ là $y = ax + b$. Tính giá trị biểu thức $T = a + b$.
- **Câu TLN 3 [Vận dụng • Dạng 1 & Dạng 2]:** Tìm tổng số đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{x + 2}{x^2 - 4x + 3}$.
- **Câu TLN 4 [Vận dụng • Dạng 1 & Dạng 2]:** Chi phí trung bình (triệu đồng) để sản xuất $x$ sản phẩm là $\overline{C}(x) = \dfrac{5x + 100}{x}$ ($x \ge 1$). Khi $x$ rất lớn ($x \to +\infty$), chi phí trung bình tiến dần đến bao nhiêu triệu đồng?
- **Câu TLN 5 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{4x - 1}{x - 2}$ tạo với hai trục tọa độ một hình chữ nhật có chu vi bằng bao nhiêu?
- **Câu TLN 6 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Tìm giá trị của tham số $m$ để đồ thị hàm số $y = \dfrac{2x + 3}{x - m}$ có đường tiệm cận đứng đi qua điểm $A(5; 2)$.

#### PHẦN IV. Tự luận (Dành cho Dạng 1 gồm 4 phần 21 câu: 3 câu × 1,0 điểm = 3,0 điểm)
- **Câu 19 [1,0đ • Tự luận 1 • Tìm TCĐ và TCX của đồ thị hàm phân thức]:** Câu 19 (1,0 điểm): Tìm tất cả các đường tiệm cận của đồ thị hàm số $y = f(x) = \dfrac{2x^2 - 3x - 1}{x - 2}$.
- **Câu 20 [1,0đ • Tự luận 2 • Biện luận tiệm cận đứng khi tử và mẫu có nghiệm chung]:** Câu 20 (1,0 điểm): Tìm tất cả các đường tiệm cận đứng và tiệm cận ngang của đồ thị hàm số $y = \dfrac{x - 1}{x^2 - 3x + 2}$.
- **Câu 21 [1,0đ • Tự luận 3 • Định tham số a, b từ giao điểm tiệm cận]:** Câu 21 (1,0 điểm): Cho hàm số $y = \dfrac{ax + 1}{bx - 2}$. Xác định $a, b$ biết đồ thị hàm số có tiệm cận đứng là $x = 1$ và tiệm cận ngang là $y = 3$.

> **Đáp án & Hướng dẫn chấm Đề 3 (Bài 3):**
> - **Phần I (12 câu TN):** 1.B | 2.B | 3.B | 4.A | 5.A | 6.A | 7.A | 8.A | 9.A | 10.A | 11.A | 12.A.
> - **Phần II (4 câu Đ/S):** **Câu Đ/S 1:** a) Đ, b) S, c) S, d) Đ | **Câu Đ/S 2:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 3:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 4:** a) Đ, b) Đ, c) S, d) Đ.
> - **Phần III (6 câu TLN):** TLN 1: `1` | TLN 2: `1` | TLN 3: `3` | TLN 4: `5` | TLN 5: `12` | TLN 6: `5`.
> - **Phần IV — Câu 19 [1,0đ • Tự luận 1 • Tìm TCĐ và TCX của đồ thị hàm phân thức]:** TXĐ D = R \ {2}. Chia đa thức y' / hàm số: y = 2x + 1 + 1/(x - 2). Vì lim(x->2+) f(x) = +vc nên x = 2 là TCĐ. Vì lim(x->+-vc) [f(x) - (2x + 1)] = 0 nên y = 2x + 1 là TCX. *(Rubric: TXĐ D = R\{2} & chỉ ra TCĐ x = 2 (0,5đ) • Tách y = 2x + 1 + 1/(x-2) và kết luận TCX y = 2x + 1 (0,5đ).)*
> - **Phần IV — Câu 20 [1,0đ • Tự luận 2 • Biện luận tiệm cận đứng khi tử và mẫu có nghiệm chung]:** TXĐ D = R \ {1; 2}. Với x != 1, x != 2 ta rút gọn y = 1/(x - 2). Khi x -> +-vc thì y -> 0 nên TCN là y = 0. Khi x -> 1 thì y -> -1 (hữu hạn) nên x = 1 không là TCĐ. Khi x -> 2+ thì y -> +vc nên x = 2 là TCĐ duy nhất. *(Rubric: Tìm TCN y = 0 (0,25đ) • Rút gọn y = 1/(x - 2), loại x = 1 và kết luận chỉ có 1 TCĐ là x = 2 (0,75đ).)*
> - **Phần IV — Câu 21 [1,0đ • Tự luận 3 • Định tham số a, b từ giao điểm tiệm cận]:** Đồ thị có TCĐ x = 2/b = 1 => b = 2. Khi đó TCN là y = a/b = a/2 = 3 => a = 6. Thử lại với a = 6, b = 2: hàm số y = (6x + 1)/(2x - 2) thỏa mãn yêu cầu. *(Rubric: Từ TCĐ x = 1 tìm được b = 2 (0,5đ) • Từ TCN y = 3 tìm được a = 6 và kiểm tra điều kiện (0,5đ).)*

---

### ĐỀ KIỂM TRA SỐ 4 — ĐỀ KIỂM TRA BÀI 4 (CHUẨN CÔNG VĂN 7991): KHẢO SÁT SỰ BIẾN THIÊN VÀ VẼ ĐỒ THỊ CỦA HÀM SỐ — SGK TOÁN 12 KNTT

#### PHẦN I. Câu trắc nghiệm nhiều phương án lựa chọn (12 câu — Dùng cho cả Dạng 1 & Dạng 2: 3,0 điểm)
- **Câu 1 [Biết]:** Tâm đối xứng của đồ thị hàm số bậc ba $y = x^3 - 3x^2 + 1$ là điểm nào dưới đây?
  - A. $I(1; 1)$
  - B. $I(1; -1)$
  - C. $I(0; 1)$
  - D. $I(2; -3)$
- **Câu 2 [Biết]:** Tâm đối xứng của đồ thị hàm số phân thức $y = \dfrac{2x - 3}{x + 2}$ là điểm nào dưới đây?
  - A. $I(2; -2)$
  - B. $I(-2; 2)$
  - C. $I(2; 2)$
  - D. $I(-2; -3)$
- **Câu 3 [Biết]:** Đồ thị hàm số $y = x^3 - 3x^2 + 4$ cắt trục tung $Oy$ tại điểm có tung độ bằng:
  - A. $4$
  - B. $0$
  - C. $2$
  - D. $-4$
- **Câu 4 [Biết]:** Đồ thị hàm số $y = \dfrac{2x - 4}{x + 1}$ cắt trục hoành $Ox$ tại điểm nào dưới đây?
  - A. $M(2; 0)$
  - B. $M(0; -4)$
  - C. $M(-1; 0)$
  - D. $M(4; 0)$
- **Câu 5 [Biết]:** Cho hàm số bậc ba $y = ax^3 + bx^2 + cx + d$ có đồ thị mà nhánh ngoài cùng bên phải đi xuống khi $x \to +\infty$. Khẳng định nào đúng?
  - A. $a < 0$
  - B. $a > 0$
  - C. $d < 0$
  - D. $c < 0$
- **Câu 6 [Biết]:** Đồ thị hàm số $y = \dfrac{x - 2}{x + 1}$ có bao nhiêu điểm cực trị?
  - A. $0$
  - B. $1$
  - C. $2$
  - D. $3$
- **Câu 7 [Biết]:** Tâm đối xứng của đồ thị hàm số $y = x + 1 + \dfrac{2}{x - 1}$ là điểm nào dưới đây?
  - A. $I(1; 2)$
  - B. $I(1; 1)$
  - C. $I(-1; 2)$
  - D. $I(2; 1)$
- **Câu 8 [Biết]:** Đồ thị hàm số bậc ba $y = ax^3 + bx^2 + cx + d \ (a \ne 0)$ và một đường thẳng cắt nhau tại tối đa bao nhiêu giao điểm?
  - A. $3$
  - B. $2$
  - C. $4$
  - D. $1$
- **Câu 9 [Hiểu]:** Đường cong đi qua $(0; 2)$, đạt cực đại tại $(-1; 4)$ và đạt cực tiểu tại $(1; 0)$ là đồ thị của hàm số nào?
  - A. $y = x^3 - 3x + 2$
  - B. $y = -x^3 + 3x + 2$
  - C. $y = x^3 - 3x^2 + 2$
  - D. $y = x^3 + 3x + 2$
- **Câu 10 [Hiểu]:** Cho hàm số $y = ax^3 + bx^2 + cx + d$ có nhánh phải đi lên, cắt trục tung phía trên $Ox$ và có 2 điểm cực trị trái dấu ($x_1 < 0 < x_2$). Mệnh đề nào đúng?
  - A. $a > 0,\ c < 0,\ d > 0$
  - B. $a > 0,\ c > 0,\ d > 0$
  - C. $a < 0,\ c > 0,\ d > 0$
  - D. $a > 0,\ c < 0,\ d < 0$
- **Câu 11 [Hiểu]:** Số giao điểm của đồ thị hàm số $y = x^3 - 3x + 1$ và đường thẳng $y = 4$ là:
  - A. $1$
  - B. $3$
  - C. $2$
  - D. $0$
- **Câu 12 [Vận dụng]:** Cho hàm số $y = x^3 - 3x^2 + 2$. Tập hợp các giá trị của $m$ để phương trình $x^3 - 3x^2 + 2 = m$ có $3$ nghiệm thực phân biệt là:
  - A. $(-2; 2)$
  - B. $[-2; 2]$
  - C. $(0; 2)$
  - D. $(-\infty; 2)$

#### PHẦN II. Câu trắc nghiệm Đúng / Sai (Dạng 1 lấy 2 câu đầu = 2,0đ; Dạng 2 lấy đủ 4 câu = 4,0đ)
- **Câu Đ/S 1 (Dạng 1 & Dạng 2):** Cho hàm số phân thức $y = \dfrac{2x - 1}{x - 1}$ có đồ thị $(C)$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đồ thị $(C)$ có tiệm cận đứng là $x = 1$ và tiệm cận ngang là $y = 2$. *[Biết]*
  - b) Tâm đối xứng của đồ thị $(C)$ là điểm $I(2; 1)$. *[Biết]*
  - c) Hàm số đồng biến trên từng khoảng $(-\infty; 1)$ và $(1; +\infty)$. *[Hiểu]*
  - d) Đồ thị $(C)$ cắt đường thẳng $y = x + 1$ tại hai điểm phân biệt. *[Vận dụng]*
- **Câu Đ/S 2 (Dạng 1 & Dạng 2):** Cho hàm số bậc ba $y = x^3 - 3x^2 + 2$ có đồ thị $(C')$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đồ thị $(C')$ cắt trục tung tại điểm $(0; 2)$. *[Biết]*
  - b) Điểm cực tiểu của đồ thị $(C')$ là $B(2; -2)$. *[Biết]*
  - c) Tâm đối xứng của đồ thị $(C')$ là điểm $I(1; 2)$. *[Hiểu]*
  - d) Đường thẳng $y = 1$ cắt đồ thị $(C')$ tại $3$ điểm phân biệt. *[Vận dụng]*
- **Câu Đ/S 3 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số phân thức $y = f(x) = \dfrac{x^2 - x + 1}{x - 1}$ có đồ thị $(C)$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Đồ thị $(C)$ có tiệm cận đứng là $x = 1$. *[Biết]*
  - b) Đồ thị $(C)$ có tiệm cận xiên là đường thẳng $y = x$. *[Biết]*
  - c) Hàm số đã cho không có điểm cực trị. *[Hiểu]*
  - d) Tâm đối xứng của đồ thị $(C)$ là điểm $I(1; 1)$. *[Vận dụng]*
- **Câu Đ/S 4 (Dành thêm cho Dạng 2 (22 câu)):** Cho hàm số bậc ba $y = f(x) = -x^3 + 3x + 1$ có đồ thị $(C')$. Xét tính đúng/sai của các mệnh đề sau:
  - a) Khi $x \to +\infty$ thì $y \to -\infty$. *[Biết]*
  - b) Đồ thị $(C')$ có tâm đối xứng là điểm $I(0; 1)$. *[Biết]*
  - c) Hàm số đồng biến trên khoảng $(1; +\infty)$. *[Hiểu]*
  - d) Phương trình $-x^3 + 3x + 1 = 0$ có $3$ nghiệm thực phân biệt. *[Vận dụng]*

#### PHẦN III. Câu trắc nghiệm Trả lời ngắn (Dạng 1 lấy 4 câu đầu = 2,0đ; Dạng 2 lấy đủ 6 câu = 3,0đ)
- **Câu TLN 1 [Hiểu • Dạng 1 & Dạng 2]:** Đồ thị hàm số $y = x^3 - 3x^2 + 5$ cắt trục tung $Oy$ tại điểm $M(0; y_0)$. Giá trị của $y_0$ bằng bao nhiêu?
- **Câu TLN 2 [Hiểu • Dạng 1 & Dạng 2]:** Cho hàm số bậc ba $y = ax^3 + bx^2 + cx + d$ đạt cực đại tại $(0; 2)$ và đạt cực tiểu tại $(2; -2)$. Tính giá trị của $y(3)$.
- **Câu TLN 3 [Vận dụng • Dạng 1 & Dạng 2]:** Gọi $I(x_0; y_0)$ là tâm đối xứng của đồ thị hàm số $y = x^3 - 6x^2 + 9x + 1$. Tính tổng $x_0 + y_0$.
- **Câu TLN 4 [Vận dụng • Dạng 1 & Dạng 2]:** Có bao nhiêu giá trị nguyên của tham số $m$ để đường thẳng $y = m$ cắt đồ thị hàm số $y = x^3 - 3x^2 + 2$ tại $3$ điểm phân biệt?
- **Câu TLN 5 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Đồ thị hàm số $y = x^3 - 3x^2 + 2$ và đường thẳng $y = x - 1$ cắt nhau tại bao nhiêu điểm phân biệt?
- **Câu TLN 6 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Biết đồ thị hàm số $y = \dfrac{ax + 2}{x + b}$ có tiệm cận đứng $x = 1$ và tiệm cận ngang $y = 3$. Tính tổng $a + b$.

#### PHẦN IV. Tự luận (Dành cho Dạng 1 gồm 4 phần 21 câu: 3 câu × 1,0 điểm = 3,0 điểm)
- **Câu 19 [1,0đ • Tự luận 1 • Khảo sát sự biến thiên và vẽ đồ thị hàm bậc ba]:** Câu 19 (1,0 điểm): Khảo sát sự biến thiên và xác định các điểm cực trị, tâm đối xứng của đồ thị hàm số $y = x^3 - 3x^2 + 2$.
- **Câu 20 [1,0đ • Tự luận 2 • Khảo sát hàm phân thức bậc nhất trên bậc nhất]:** Câu 20 (1,0 điểm): Khảo sát sự biến thiên, tìm các đường tiệm cận và giao điểm với hai trục tọa độ của đồ thị hàm số $y = \dfrac{2x - 1}{x - 1}$.
- **Câu 21 [1,0đ • Tự luận 3 • Biện luận số nghiệm phương trình bằng đồ thị]:** Câu 21 (1,0 điểm): Dựa vào bảng biến thiên của hàm số $y = x^3 - 3x^2 + 2$, hãy biện luận theo tham số $m$ số nghiệm thực của phương trình $x^3 - 3x^2 + 2 - m = 0$.

> **Đáp án & Hướng dẫn chấm Đề 4 (Bài 4):**
> - **Phần I (12 câu TN):** 1.B | 2.B | 3.A | 4.A | 5.A | 6.A | 7.A | 8.A | 9.A | 10.A | 11.A | 12.A.
> - **Phần II (4 câu Đ/S):** **Câu Đ/S 1:** a) Đ, b) S, c) S, d) Đ | **Câu Đ/S 2:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 3:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 4:** a) Đ, b) Đ, c) S, d) Đ.
> - **Phần III (6 câu TLN):** TLN 1: `5` | TLN 2: `2` | TLN 3: `5` | TLN 4: `3` | TLN 5: `3` | TLN 6: `2`.
> - **Phần IV — Câu 19 [1,0đ • Tự luận 1 • Khảo sát sự biến thiên và vẽ đồ thị hàm bậc ba]:** TXĐ D = R. Ta có y' = 3x^2 - 6x = 0 <=> x = 0 hoặc x = 2. Hàm số ĐB trên (-vc; 0) và (2; +vc), NB trên (0; 2). Điểm CĐ (0; 2), điểm CT (2; -2), tâm đối xứng I(1; 0). *(Rubric: TXĐ & giới hạn tại vô cực (0,25đ) • Tính y'=3x^2-6x, lập BBT đúng (0,5đ) • Nêu đúng CĐ(0;2), CT(2;-2), tâm đối xứng I(1;0) (0,25đ).)*
> - **Phần IV — Câu 20 [1,0đ • Tự luận 2 • Khảo sát hàm phân thức bậc nhất trên bậc nhất]:** TXĐ D = R \ {1}. y' = -1/(x - 1)^2 < 0 với mọi x != 1 => hàm số nghịch biến trên (-vc; 1) và (1; +vc). TCĐ x = 1, TCN y = 2, tâm đối xứng I(1; 2). Giao Oy tại (0; 1), giao Ox tại (1/2; 0). *(Rubric: TXĐ, tính y' = -1/(x-1)^2 < 0 và lập BBT (0,5đ) • Chỉ ra TCĐ x = 1, TCN y = 2 và giao điểm với Ox, Oy (0,5đ).)*
> - **Phần IV — Câu 21 [1,0đ • Tự luận 3 • Biện luận số nghiệm phương trình bằng đồ thị]:** Phương trình tương đương x^3 - 3x^2 + 2 = m. Với y_CD = 2, y_CT = -2: Nếu m > 2 hoặc m < -2 thì PT có 1 nghiệm; nếu m = 2 hoặc m = -2 thì PT có 2 nghiệm; nếu -2 < m < 2 thì PT có 3 nghiệm phân biệt. *(Rubric: Đưa về tương giao y = x^3 - 3x^2 + 2 và y = m (0,25đ) • Biện luận đầy đủ 3 trường hợp của m (0,75đ).)*

---

### ĐỀ KIỂM TRA SỐ 5 — ĐỀ KIỂM TRA BÀI 5 (CHUẨN CÔNG VĂN 7991): ỨNG DỤNG ĐẠO HÀM ĐỂ GIẢI QUYẾT VẤN ĐỀ THỰC TIỄN — SGK TOÁN 12 KNTT

#### PHẦN I. Câu trắc nghiệm nhiều phương án lựa chọn (12 câu — Dùng cho cả Dạng 1 & Dạng 2: 3,0 điểm)
- **Câu 1 [Biết]:** Một chất điểm chuyển động theo phương trình $s = s(t)$. Vận tốc tức thời $v(t)$ tại thời điểm $t$ được tính bằng:
  - A. $v(t) = s''(t)$
  - B. $v(t) = s'(t)$
  - C. $v(t) = \dfrac{s(t)}{t}$
  - D. $v(t) = s(t)$
- **Câu 2 [Biết]:** Nếu hàm tổng doanh thu là $R(x)$ và hàm tổng chi phí là $C(x)$ thì hàm tổng lợi nhuận $P(x)$ là:
  - A. $P(x) = R(x) + C(x)$
  - B. $P(x) = R(x) - C(x)$
  - C. $P(x) = \dfrac{R(x)}{C(x)}$
  - D. $P(x) = C(x) - R(x)$
- **Câu 3 [Biết]:** Cho hàm tổng chi phí sản xuất $x$ đơn vị sản phẩm là $C(x) = x^2 + 40x + 500$. Hàm chi phí biên $C'(x)$ là:
  - A. $C'(x) = 2x + 40$
  - B. $C'(x) = x + 40$
  - C. $C'(x) = 2x + 500$
  - D. $C'(x) = x^2 + 40$
- **Câu 4 [Biết]:** Nồng độ thuốc trong máu bệnh nhân sau $t$ giờ kể từ khi tiêm là $C(t) = \dfrac{2t}{t^2 + 4}\text{ (mg/lít)}$ ($t \ge 0$). Nồng độ thuốc đạt lớn nhất tại thời điểm:
  - A. $t = 2$ giờ
  - B. $t = 1$ giờ
  - C. $t = 4$ giờ
  - D. $t = 0{,}5$ giờ
- **Câu 5 [Biết]:** Một vật chuyển động với vận tốc $v(t) = 3t^2 - 12t\text{ (m/s)}$. Gia tốc tức thời của vật tại thời điểm $t = 3\text{ (s)}$ bằng:
  - A. $6\text{ m/s}^2$
  - B. $12\text{ m/s}^2$
  - C. $0\text{ m/s}^2$
  - D. $-9\text{ m/s}^2$
- **Câu 6 [Biết]:** Một chất điểm chuyển động theo quy luật $s(t) = -t^3 + 6t^2 + 9t$ ($t$ tính bằng giây, $s$ tính bằng mét). Vận tốc lớn nhất của chất điểm trong khoảng $[0; 4]$ giây là:
  - A. $21\text{ m/s}$
  - B. $15\text{ m/s}$
  - C. $24\text{ m/s}$
  - D. $18\text{ m/s}$
- **Câu 7 [Biết]:** Số lượng vi khuẩn sau $t$ giờ được tính bởi $N(t) = 1000 + 50t^2$. Tốc độ tăng trưởng tức thời của quần thể vi khuẩn tại thời điểm $t = 2$ giờ là:
  - A. $200$ vi khuẩn/giờ
  - B. $100$ vi khuẩn/giờ
  - C. $1200$ vi khuẩn/giờ
  - D. $400$ vi khuẩn/giờ
- **Câu 8 [Biết]:** Nếu giá bán mỗi sản phẩm là $p(x) = 200 - 2x$ (nghìn đồng) thì hàm tổng doanh thu $R(x)$ khi bán $x$ sản phẩm là:
  - A. $R(x) = 200x - 2x^2$
  - B. $R(x) = 200 - 2x^2$
  - C. $R(x) = 200 - 4x$
  - D. $R(x) = 2x^2 - 200x$
- **Câu 9 [Hiểu]:** Từ tấm bìa hình vuông cạnh $30\text{ cm}$, người ta cắt ở 4 góc 4 hình vuông bằng nhau cạnh $x\text{ (cm)}$ rồi gấp thành hộp không nắp. Để thể tích hộp lớn nhất thì $x$ bằng:
  - A. $5\text{ cm}$
  - B. $6\text{ cm}$
  - C. $10\text{ cm}$
  - D. $3\text{ cm}$
- **Câu 10 [Hiểu]:** Doanh nghiệp sản xuất $x$ sản phẩm/ngày ($1 \le x \le 100$) có chi phí $C(x) = x^2 + 30x + 400$ và doanh thu $R(x) = 150x$ (nghìn đồng). Số sản phẩm cần sản xuất để lợi nhuận lớn nhất là:
  - A. $60$ sản phẩm
  - B. $50$ sản phẩm
  - C. $40$ sản phẩm
  - D. $75$ sản phẩm
- **Câu 11 [Hiểu]:** Dùng $60\text{ m}$ lưới thép rào 3 cạnh của một khu vườn hình chữ nhật sát bờ tường thẳng có sẵn. Diện tích lớn nhất của khu vườn là:
  - A. $450\text{ m}^2$
  - B. $400\text{ m}^2$
  - C. $900\text{ m}^2$
  - D. $300\text{ m}^2$
- **Câu 12 [Vận dụng]:** Chi phí sản xuất $x$ sản phẩm ($x > 0$) là $C(x) = x^2 + 20x + 100$ (triệu đồng). Chi phí trung bình $\overline{C}(x) = \dfrac{C(x)}{x}$ đạt giá trị nhỏ nhất khi sản xuất bao nhiêu sản phẩm?
  - A. $10$ sản phẩm
  - B. $20$ sản phẩm
  - C. $5$ sản phẩm
  - D. $15$ sản phẩm

#### PHẦN II. Câu trắc nghiệm Đúng / Sai (Dạng 1 lấy 2 câu đầu = 2,0đ; Dạng 2 lấy đủ 4 câu = 4,0đ)
- **Câu Đ/S 1 (Dạng 1 & Dạng 2):** Một doanh nghiệp sản xuất $x$ sản phẩm mỗi ngày ($1 \le x \le 100$) có tổng chi phí $C(x) = x^2 + 30x + 400$ (nghìn đồng) và tổng doanh thu $R(x) = 150x$ (nghìn đồng). Xét tính đúng/sai của các mệnh đề sau:
  - a) Hàm chi phí biên của doanh nghiệp là $C'(x) = 2x + 30$. *[Biết]*
  - b) Hàm lợi nhuận là $P(x) = x^2 - 120x + 400$ (nghìn đồng). *[Biết]*
  - c) Để lợi nhuận lớn nhất thì doanh nghiệp cần sản xuất $50$ sản phẩm mỗi ngày. *[Hiểu]*
  - d) Lợi nhuận tối đa mà doanh nghiệp thu được trong ngày là $3200$ nghìn đồng. *[Vận dụng]*
- **Câu Đ/S 2 (Dạng 1 & Dạng 2):** Một vật được phóng thẳng đứng lên trên từ mặt đất với phương trình độ cao $h(t) = 20t - 5t^2$ ($t \ge 0$ tính bằng giây, $h$ tính bằng mét). Xét tính đúng/sai của các mệnh đề sau:
  - a) Vận tốc tức thời của vật tại thời điểm $t$ là $v(t) = 20 - 10t\text{ (m/s)}$. *[Biết]*
  - b) Vật đạt độ cao lớn nhất tại thời điểm $t = 2$ giây. *[Biết]*
  - c) Độ cao lớn nhất mà vật đạt được là $25\text{ m}$. *[Hiểu]*
  - d) Vật chạm đất trở lại tại thời điểm $t = 4$ giây với vận tốc chạm đất có độ lớn bằng $20\text{ m/s}$. *[Vận dụng]*
- **Câu Đ/S 3 (Dành thêm cho Dạng 2 (22 câu)):** Từ một tấm tôn hình vuông cạnh $12\text{ dm}$, người ta cắt ở 4 góc 4 hình vuông bằng nhau cạnh $x\text{ (dm)}$ ($0 < x < 6$) rồi gấp lên thành một chiếc hộp không nắp. Xét tính đúng/sai của các mệnh đề sau:
  - a) Chiều rộng và chiều dài đáy hộp sau khi gấp đều bằng $12 - 2x\text{ (dm)}$. *[Biết]*
  - b) Thể tích chiếc hộp theo $x$ là $V(x) = x(12 - 2x)^2\text{ (dm}^3\text{)}$. *[Biết]*
  - c) Thể tích chiếc hộp đạt lớn nhất khi $x = 3\text{ dm}$. *[Hiểu]*
  - d) Thể tích lớn nhất của chiếc hộp bằng $128\text{ dm}^3$. *[Vận dụng]*
- **Câu Đ/S 4 (Dành thêm cho Dạng 2 (22 câu)):** Một cơ sở sản xuất $x$ sản phẩm ($x > 0$) có tổng chi phí $C(x) = x^2 + 20x + 100$ (triệu đồng). Xét tính đúng/sai của các mệnh đề sau:
  - a) Chi phí trung bình cho mỗi sản phẩm là $\overline{C}(x) = x + 20 + \dfrac{100}{x}$. *[Biết]*
  - b) Đạo hàm của hàm chi phí trung bình là $\overline{C}'(x) = 1 - \dfrac{100}{x^2}$. *[Biết]*
  - c) Chi phí trung bình đạt nhỏ nhất khi sản xuất $x = 20$ sản phẩm. *[Hiểu]*
  - d) Giá trị nhỏ nhất của chi phí trung bình là $40$ triệu đồng/sản phẩm. *[Vận dụng]*

#### PHẦN III. Câu trắc nghiệm Trả lời ngắn (Dạng 1 lấy 4 câu đầu = 2,0đ; Dạng 2 lấy đủ 6 câu = 3,0đ)
- **Câu TLN 1 [Hiểu • Dạng 1 & Dạng 2]:** Từ tấm bìa hình vuông cạnh $30\text{ cm}$, cắt 4 góc 4 hình vuông cạnh $x\text{ (cm)}$ để gấp thành hộp không nắp có thể tích lớn nhất. Giá trị của $x$ bằng bao nhiêu $\text{cm}$?
- **Câu TLN 2 [Hiểu • Dạng 1 & Dạng 2]:** Một trang sách hình chữ nhật có diện tích phần in chữ là $384\text{ cm}^2$, lề trên và dưới rộng $3\text{ cm}$, lề trái và phải rộng $2\text{ cm}$. Diện tích nhỏ nhất của trang sách bằng bao nhiêu $\text{cm}^2$?
- **Câu TLN 3 [Vận dụng • Dạng 1 & Dạng 2]:** Một cửa hàng bán mỗi chiếc áo giá $200$ nghìn đồng thì bán được $100$ chiếc/tuần. Cứ giảm giá $10$ nghìn đồng/chiếc thì bán thêm được $10$ chiếc. Hỏi cần giảm giá bao nhiêu lần $10$ nghìn đồng (tức tìm $x$) để doanh thu lớn nhất?
- **Câu TLN 4 [Vận dụng • Dạng 1 & Dạng 2]:** Khi cắt 4 góc hình vuông cạnh $x = 2\text{ cm}$ từ tấm bìa vuông cạnh $12\text{ cm}$ để gấp thành hộp không nắp thì thể tích lớn nhất của hộp bằng bao nhiêu $\text{cm}^3$?
- **Câu TLN 5 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Xây một bể nước không nắp hình hộp chữ nhật có đáy là hình vuông cạnh $x\text{ (m)}$ và thể tích $32\text{ m}^3$. Để tổng diện tích đáy và 4 mặt xung quanh nhỏ nhất thì cạnh đáy $x$ bằng bao nhiêu mét?
- **Câu TLN 6 [Vận dụng • Dành thêm cho Dạng 2 (22 câu)]:** Một chất điểm chuyển động theo phương trình $s(t) = 12t - t^3$ ($t \ge 0$ tính bằng giây, $s$ tính bằng mét). Quãng đường chất điểm đi được từ lúc $t = 0$ đến lúc vận tốc bằng $0$ là bao nhiêu mét?

#### PHẦN IV. Tự luận (Dành cho Dạng 1 gồm 4 phần 21 câu: 3 câu × 1,0 điểm = 3,0 điểm)
- **Câu 19 [1,0đ • Tự luận 1 • Bài toán cắt gấp hộp tối ưu thể tích]:** Câu 19 (1,0 điểm): Từ một tấm bìa hình vuông cạnh $30\text{ cm}$, người ta cắt ở bốn góc bốn hình vuông bằng nhau cạnh $x\text{ (cm)}$ ($0 < x < 15$) rồi gấp lại thành một hình hộp chữ nhật không nắp. Lập hàm thể tích $V(x)$ và tìm $x$ để hộp có thể tích lớn nhất.
- **Câu 20 [1,0đ • Tự luận 2 • Bài toán tối ưu lợi nhuận doanh nghiệp]:** Câu 20 (1,0 điểm): Một doanh nghiệp sản xuất $x$ sản phẩm mỗi ngày ($1 \le x \le 100$) có hàm chi phí $C(x) = x^2 + 30x + 400$ (nghìn đồng) và hàm doanh thu $R(x) = 150x$ (nghìn đồng). Lập hàm lợi nhuận $P(x)$ và tìm $x$ để lợi nhuận đạt lớn nhất.
- **Câu 21 [1,0đ • Tự luận 3 • Thiết kế bể chứa nước tối ưu chi phí vật liệu]:** Câu 21 (1,0 điểm): Người ta cần xây một bể chứa nước không nắp dạng hình hộp chữ nhật có đáy là hình vuông cạnh $x\text{ (m)}$ ($x > 0$) và thể tích bằng $32\text{ m}^3$. Tìm độ dài cạnh đáy $x$ và chiều cao $h$ của bể để tổng diện tích xung quanh và diện tích đáy của bể là nhỏ nhất.

> **Đáp án & Hướng dẫn chấm Đề 5 (Bài 5):**
> - **Phần I (12 câu TN):** 1.B | 2.B | 3.A | 4.A | 5.A | 6.A | 7.A | 8.A | 9.A | 10.A | 11.A | 12.A.
> - **Phần II (4 câu Đ/S):** **Câu Đ/S 1:** a) Đ, b) S, c) S, d) Đ | **Câu Đ/S 2:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 3:** a) Đ, b) Đ, c) S, d) Đ | **Câu Đ/S 4:** a) Đ, b) Đ, c) S, d) Đ.
> - **Phần III (6 câu TLN):** TLN 1: `5` | TLN 2: `600` | TLN 3: `5` | TLN 4: `128` | TLN 5: `4` | TLN 6: `16`.
> - **Phần IV — Câu 19 [1,0đ • Tự luận 1 • Bài toán cắt gấp hộp tối ưu thể tích]:** Điều kiện 0 < x < 15. Thể tích V(x) = x(30 - 2x)^2. Đạo hàm y' = V'(x) = (30 - 2x)(30 - 6x) = 0 => x = 5 cm. Khi đó V_max = 2000 cm^3. *(Rubric: Điều kiện 0 < x < 15 & lập hàm V(x) = x(30-2x)^2 (0,5đ) • Giải V'(x) = 0 => x = 5 cm, V_max = 2000 cm^3 (0,5đ).)*
> - **Phần IV — Câu 20 [1,0đ • Tự luận 2 • Bài toán tối ưu lợi nhuận doanh nghiệp]:** Hàm lợi nhuận P(x) = R(x) - C(x) = -x^2 + 120x - 400. Ta có P'(x) = -2x + 120 = 0 <=> x = 60 thuộc [1; 100]. Vậy cần sản xuất 60 sản phẩm/ngày để đạt lợi nhuận tối đa P(60) = 3200 nghìn đồng. *(Rubric: Lập hàm P(x) = -x^2 + 120x - 400 (0,5đ) • Giải P'(x) = 0 tìm được x = 60 sản phẩm và P_max = 3200 nghìn đồng (0,5đ).)*
> - **Phần IV — Câu 21 [1,0đ • Tự luận 3 • Thiết kế bể chứa nước tối ưu chi phí vật liệu]:** Thể tích V = x^2.h = 32 => h = 32/x^2. Tổng diện tích cần xây S(x) = x^2 + 4xh = x^2 + 128/x (x > 0). Đạo hàm S'(x) = 2x - 128/x^2 = 0 <=> x^3 = 64 <=> x = 4 (m). Khi đó chiều cao h = 32/16 = 2 (m) và S_min = 48 m^2. *(Rubric: Biểu diễn h = 32/x^2 và lập hàm diện tích S(x) = x^2 + 128/x (0,5đ) • Giải S'(x) = 0 tìm được x = 4 m, h = 2 m (0,5đ).)*
