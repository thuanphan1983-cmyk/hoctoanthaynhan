# TỔNG HỢP TOÀN BỘ LÝ THUYẾT, DẠNG TOÁN VÀ ĐỀ KIỂM TRA CHUẨN CÔNG VĂN 7991

## CÁC CHƯƠNG CÒN LẠI CỦA SÁCH TOÁN 12 KẾT NỐI TRI THỨC VỚI CUỘC SỐNG

### (GỒM CHƯƠNG III, CHƯƠNG IV, CHƯƠNG V, CHƯƠNG VI — TẬP 1 VÀ TẬP 2)

**Hệ thống học tập: Học Toán Thầy Nhẫn | Chuẩn Công văn 7991/BGDĐT-GDTrH**

## MỤC LỤC TỔNG THỂ

1. **CHƯƠNG III: CÁC SỐ ĐẶC TRƯNG ĐO MỨC ĐỘ PHÂN TÁN CHO MẪU SỐ LIỆU GHÉP NHÓM**

   * Bài 9: Khoảng biến thiên và khoảng tứ phân vị của mẫu số liệu ghép nhóm

   * Bài 10: Phương sai và độ lệch chuẩn của mẫu số liệu ghép nhóm

   * Hệ thống 20 bài tập tự luận rèn luyện kỹ năng (10 bài/dạng: 4 Biết – 3 Hiểu – 3 Vận dụng)

   * Đề kiểm tra Chương III chuẩn Công văn 7991 (2 Dạng đề)

2. **CHƯƠNG IV: NGUYÊN HÀM VÀ TÍCH PHÂN**

   * Bài 11: Nguyên hàm

   * Bài 12: Tích phân

   * Bài 13: Ứng dụng hình học của tích phân (Diện tích & Thể tích)

   * Hệ thống 30 bài tập tự luận rèn luyện kỹ năng (10 bài/dạng: 4 Biết – 3 Hiểu – 3 Vận dụng)

   * Đề kiểm tra Chương IV chuẩn Công văn 7991 (2 Dạng đề)

3. **CHƯƠNG V: PHƯƠNG PHÁP TOẠ ĐỘ TRONG KHÔNG GIAN**

   * Bài 14: Phương trình mặt phẳng

   * Bài 15: Phương trình đường thẳng trong không gian

   * Bài 16: Công thức tính góc trong không gian

   * Bài 17: Phương trình mặt cầu

   * Hệ thống 40 bài tập tự luận rèn luyện kỹ năng (10 bài/dạng: 4 Biết – 3 Hiểu – 3 Vận dụng)

   * Đề kiểm tra Chương V chuẩn Công văn 7991 (2 Dạng đề)

4. **CHƯƠNG VI: XÁC SUẤT CÓ ĐIỀU KIỆN**

   * Bài 18: Xác suất có điều kiện

   * Bài 19: Công thức xác suất toàn phần và công thức Bayes

   * Hệ thống 20 bài tập tự luận rèn luyện kỹ năng (10 bài/dạng: 4 Biết – 3 Hiểu – 3 Vận dụng)

   * Đề kiểm tra Chương VI chuẩn Công văn 7991 (2 Dạng đề)

# PHẦN 1. CHƯƠNG III: CÁC SỐ ĐẶC TRƯNG ĐO MỨC ĐỘ PHÂN TÁN CHO MẪU SỐ LIỆU GHÉP NHÓM

## A. LÝ THUYẾT TRỌNG TÂM CHƯƠNG III

### 1. Bài 9: Khoảng biến thiên và khoảng tứ phân vị của mẫu số liệu ghép nhóm

* **Mẫu số liệu ghép nhóm:** Bảng tần số ghép nhóm gồm $k$ nhóm $[u_1; u_2), [u_2; u_3), \dots, [u_k; u_{k+1})$ với tần số tương ứng $n_1, n_2, \dots, n_k$ và cỡ mẫu $n = \sum_{i=1}^k n_i$.

* **Khoảng biến thiên:** $R = u_{k+1} - u_1$ (hiệu giữa đầu mút phải của nhóm cuối cùng và đầu mút trái của nhóm đầu tiên).

* **Khoảng tứ phân vị:** $\Delta_Q = Q_3 - Q_1$.

  * **Tứ phân vị thứ nhất** $Q_1$**:** Nhóm chứa $Q_1$ là nhóm $[u_m; u_{m+1})$ đầu tiên có tần số tích lũy $cf_m \ge \dfrac{n}{4}$. 

    $$
    Q_1 = u_m + \dfrac{\dfrac{n}{4} - cf_{m-1}}{n_m} \cdot (u_{m+1} - u_m)
    $$

  * **Tứ phân vị thứ ba** $Q_3$**:** Nhóm chứa $Q_3$ là nhóm $[u_p; u_{p+1})$ đầu tiên có tần số tích lũy $cf_p \ge \dfrac{3n}{4}$. 

    $$
    Q_3 = u_p + \dfrac{\dfrac{3n}{4} - cf_{p-1}}{n_p} \cdot (u_{p+1} - u_p)
    $$

* **Ý nghĩa thực tế:** Khoảng tứ phân vị đo độ phân tán của $50\%$ số liệu ở phần giữa của mẫu, không bị ảnh hưởng bởi các giá trị bất thường (ngoại lai).

### 2. Bài 10: Phương sai và độ lệch chuẩn của mẫu số liệu ghép nhóm

* **Giá trị đại diện:** Mỗi nhóm $[u_i; u_{i+1})$ có giá trị đại diện là $c_i = \dfrac{u_i + u_{i+1}}{2}$.

* **Số trung bình:** 

  $$
  \bar{x} = \dfrac{n_1 c_1 + n_2 c_2 + \dots + n_k c_k}{n} = \dfrac{1}{n} \sum_{i=1}^k n_i c_i
  $$

* **Phương sai:** 

  $$
  s^2 = \dfrac{1}{n} \sum_{i=1}^k n_i c_i^2 - \bar{x}^2 = \dfrac{1}{n} \sum_{i=1}^k n_i (c_i - \bar{x})^2
  $$

* **Độ lệch chuẩn:** $s = \sqrt{s^2}$.

* **Ý nghĩa thực tế:** Phương sai và độ lệch chuẩn càng lớn thì số liệu càng phân tán xa số trung bình; ngược lại, càng nhỏ thì số liệu càng tập trung, độ đồng đều (ổn định) càng cao.

## B. HỆ THỐNG 20 BÀI TẬP TỰ LUYỆN TỰ LUẬN CHƯƠNG III (4 BIẾT – 3 HIỂU – 3 VẬN DỤNG)

### DẠNG 3.1: KHOẢNG BIẾN THIÊN VÀ KHOẢNG TỨ PHÂN VỊ CỦA MẪU SỐ LIỆU GHÉP NHÓM (10 BÀI TỰ LUẬN)

* **Bài 9.1 \[Nhận biết\]:** Cho mẫu số liệu ghép nhóm về chiều cao (cm) của 40 học sinh: $[150; 155): 5; [155; 160): 12; [160; 165): 15; [165; 170): 8$. Xác định khoảng biến thiên $R$ của mẫu số liệu. *Lời giải:* $R = 170 - 150 = 20\text{ cm}$.

* **Bài 9.2 \[Nhận biết\]:** Nêu công thức tính tứ phân vị thứ nhất $Q_1$ của mẫu số liệu ghép nhóm và giải thích rõ từng ký hiệu trong công thức. *Lời giải:* $Q_1 = u_m + \dfrac{n/4 - cf_{m-1}}{n_m} \cdot (u_{m+1} - u_m)$, với $[u_m; u_{m+1})$ là nhóm chứa $Q_1$, $n$ là cỡ mẫu, $cf_{m-1}$ là tần số tích lũy nhóm trước, $n_m$ là tần số nhóm chứa $Q_1$.

* **Bài 9.3 \[Nhận biết\]:** Cho mẫu số liệu có $Q_1 = 24{,}5$ và $Q_3 = 38{,}2$. Tính khoảng tứ phân vị $\Delta_Q$ và nêu ý nghĩa. *Lời giải:* $\Delta_Q = Q_3 - Q_1 = 38{,}2 - 24{,}5 = 13{,}7$. Ý nghĩa: Khoảng chứa $50\%$ số liệu trung tâm có độ chênh lệch là $13{,}7$.

* **Bài 9.4 \[Nhận biết\]:** Cho mẫu số liệu ghép nhóm thời gian đi học (phút) của 50 học sinh có $n = 50$. Xác định vị trí nhóm chứa tứ phân vị $Q_1$ và nhóm chứa $Q_3$ dựa trên tần số tích lũy. *Lời giải:* $n/4 = 12{,}5 \Rightarrow$ nhóm chứa $Q_1$ là nhóm đầu tiên có $cf \ge 13$; $3n/4 = 37{,}5 \Rightarrow$ nhóm chứa $Q_3$ có $cf \ge 38$.

* **Bài 9.5 \[Thông hiểu\]:** Tính tứ phân vị thứ nhất $Q_1$ của mẫu số liệu sau: $[10; 20): 8; [20; 30): 14; [30; 40): 12; [40; 50): 6$ ($n = 40$). *Lời giải:* $n/4 = 10$. Nhóm chứa $Q_1$ là $[20; 30)$ có $u_m = 20, n_m = 14, cf_{m-1} = 8, h = 10$. Suy ra $Q_1 = 20 + \dfrac{10 - 8}{14} \cdot 10 = 20 + \dfrac{20}{14} \approx 21{,}43$.

* **Bài 9.6 \[Thông hiểu\]:** Với bảng số liệu ở Bài 9.5, tính tứ phân vị thứ ba $Q_3$ và khoảng tứ phân vị $\Delta_Q$. *Lời giải:* $3n/4 = 30$. Nhóm chứa $Q_3$ là $[30; 40)$ có $u_p = 30, n_p = 12, cf_{p-1} = 22, h = 10$. $Q_3 = 30 + \dfrac{30 - 22}{12} \cdot 10 = 30 + \dfrac{80}{12} \approx 36{,}67$. Khoảng tứ phân vị $\Delta_Q = 36{,}67 - 21{,}43 = 15{,}24$.

* **Bài 9.7 \[Thông hiểu\]:** So sánh khoảng biến thiên $R$ và khoảng tứ phân vị $\Delta_Q$ của mẫu số liệu ghép nhóm về mức độ nhạy cảm với các giá trị bất thường (ngoại lai). *Lời giải:* $R$ phụ thuộc vào hai giá trị biên nên rất nhạy cảm với ngoại lai; $\Delta_Q$ loại bỏ $25\%$ số liệu nhỏ nhất và $25\%$ số liệu lớn nhất nên không bị ảnh hưởng bởi ngoại lai.

* **Bài 9.8 \[Vận dụng\]:** Khảo sát thời gian truy cập internet hàng ngày (phút) của hai nhóm thanh niên Nhóm A và Nhóm B. Nhóm A có $\Delta_{Q_A} = 15\text{ phút}$, Nhóm B có $\Delta_{Q_B} = 35\text{ phút}$. Đưa ra nhận xét về độ phân tán thời gian truy cập giữa hai nhóm. *Lời giải:* Nhóm B có khoảng tứ phân vị lớn hơn nhiều so với Nhóm A ($35 > 15$), chứng tỏ thời gian truy cập internet của Nhóm B phân tán rộng hơn, mức độ đồng đều kém hơn Nhóm A.

* **Bài 9.9 \[Vận dụng\]:** Một nhà máy sản xuất linh kiện điện tử kiểm tra tuổi thọ (nghìn giờ) của 100 linh kiện thu được kết quả: $[5; 7): 10; [7; 9): 30; [9; 11): 40; [11; 13): 15; [13; 15): 5$. Hãy xác định khoảng tứ phân vị và tìm khoảng chứa $50\%$ linh kiện có tuổi thọ trung bình nhất. *Lời giải:* $n = 100 \Rightarrow n/4 = 25 \in [7; 9)$, $Q_1 = 7 + \dfrac{25 - 10}{30} \cdot 2 = 8$. $3n/4 = 75 \in [9; 11)$, $Q_3 = 9 + \dfrac{75 - 40}{40} \cdot 2 = 10{,}75$. Khoảng chứa $50\%$ linh kiện trung tâm là $[8; 10{,}75]$ nghìn giờ; $\Delta_Q = 2{,}75$ nghìn giờ.

* **Bài 9.10 \[Vận dụng\]:** Cho mẫu số liệu ghép nhóm có $n = 60$, biết $R = 40$ và khoảng tứ phân vị $\Delta_Q = 12$. Nếu thêm một nhóm quan sát ngoại lai lớn $[80; 90)$ với tần số 1, phân tích sự thay đổi của $R$ và $\Delta_Q$. *Lời giải:* $R$ sẽ tăng đột biến theo khoảng mới; $\Delta_Q$ thay đổi rất ít hoặc không đổi vì chỉ dịch chuyển nhẹ vị trí thứ hạng của 1 phần tử.

### DẠNG 3.2: PHƯƠNG SAI VÀ ĐỘ LỆCH CHUẨN CỦA MẪU SỐ LIỆU GHÉP NHÓM (10 BÀI TỰ LUẬN)

* **Bài 10.1 \[Nhận biết\]:** Nêu các bước tính số trung bình $\bar{x}$, phương sai $s^2$ và độ lệch chuẩn $s$ của một mẫu số liệu ghép nhóm. *Lời giải:* 1) Xác định giá trị đại diện $c_i = \dfrac{a_i + a_{i+1}}{2}$; 2) Tính $\bar{x} = \dfrac{\sum n_i c_i}{n}$; 3) Tính $s^2 = \dfrac{\sum n_i c_i^2}{n} - \bar{x}^2$; 4) $s = \sqrt{s^2}$.

* **Bài 10.2 \[Nhận biết\]:** Cho mẫu số liệu ghép nhóm gồm hai nhóm $[0; 10)$ có tần số $4$ và $[10; 20)$ có tần số $6$. Xác định giá trị đại diện của từng nhóm và tính số trung bình $\bar{x}$. *Lời giải:* $c_1 = 5, c_2 = 15$. $\bar{x} = \dfrac{4(5) + 6(15)}{10} = \dfrac{20 + 90}{10} = 11$.

* **Bài 10.3 \[Nhận biết\]:** Cho phương sai của một mẫu số liệu ghép nhóm là $s^2 = 16$. Tìm độ lệch chuẩn $s$ và nêu đơn vị đo của $s$ so với số liệu ban đầu. *Lời giải:* $s = \sqrt{16} = 4$. Đơn vị đo của độ lệch chuẩn cùng đơn vị với số liệu ban đầu.

* **Bài 10.4 \[Nhận biết\]:** Hai lớp 12A và 12B có điểm thi trung bình môn Toán đều bằng $7{,}5$. Độ lệch chuẩn của lớp 12A là $s_A = 0{,}8$ và lớp 12B là $s_B = 1{,}5$. Lớp nào có kết quả học tập đồng đều hơn? *Lời giải:* Lớp 12A có độ lệch chuẩn nhỏ hơn ($0{,}8 < 1{,}5$) nên điểm thi của lớp 12A đồng đều hơn lớp 12B.

* **Bài 10.5 \[Thông hiểu\]:** Tính số trung bình và phương sai của mẫu số liệu sau: $[20; 30): 5; [30; 40): 10; [40; 50): 5$ ($n = 20$). *Lời giải:* $c_1 = 25, c_2 = 35, c_3 = 45$. $\bar{x} = \dfrac{5(25) + 10(35) + 5(45)}{20} = 35$. $s^2 = \dfrac{5(25^2) + 10(35^2) + 5(45^2)}{20} - 35^2 = \dfrac{3125 + 12250 + 10125}{20} - 1225 = 1275 - 1225 = 50$. Độ lệch chuẩn $s = \sqrt{50} \approx 7{,}07$.

* **Bài 10.6 \[Thông hiểu\]:** Bảng số liệu ghi lại cự ly ném lao (m) của một vận động viên: $[60; 65): 2; [65; 70): 8; [70; 75): 15; [75; 80): 5$ ($n = 30$). Tính cự ly ném trung bình và độ lệch chuẩn. *Lời giải:* $c = [62{,}5; 67{,}5; 72{,}5; 77{,}5]$. $\bar{x} = \dfrac{2(62{,}5) + 8(67{,}5) + 15(72{,}5) + 5(77{,}5)}{30} = \dfrac{2140}{30} \approx 71{,}33\text{ m}$. $s^2 \approx 15{,}22 \Rightarrow s \approx 3{,}90\text{ m}$.

* **Bài 10.7 \[Thông hiểu\]:** Nếu tất cả các đầu mút nhóm của mẫu số liệu ghép nhóm đều được cộng thêm một hằng số $c$, thì phương sai và độ lệch chuẩn thay đổi như thế nào? *Lời giải:* Khi cộng thêm hằng số $c$, số trung bình tăng thêm $c$, nhưng độ lệch từng giá trị so với số trung bình $(x_i + c) - (\bar{x} + c) = x_i - \bar{x}$ không đổi, do đó phương sai và độ lệch chuẩn không đổi.

* **Bài 10.8 \[Vận dụng\]:** Một nhà đầu tư so sánh mức sinh lời hàng tháng (%) của hai quỹ cổ phiếu X và Y qua 24 tháng thu được: Quỹ X có $\bar{x}_X = 1{,}8\%$, $s_X = 0{,}6\%$; Quỹ Y có $\bar{x}_Y = 2{,}0\%$, $s_Y = 1{,}5\%$. Phân tích rủi ro và khuyến nghị lựa chọn cho nhà đầu tư thích an toàn. *Lời giải:* Quỹ Y có tỉ suất sinh lời trung bình cao hơn ($2{,}0\% > 1{,}8\%$), nhưng độ lệch chuẩn của Quỹ Y lớn hơn nhiều ($1{,}5\% > 0{,}6\%$) đồng nghĩa với độ biến động và rủi ro lớn hơn. Nhà đầu tư thích an toàn nên chọn Quỹ X vì mức sinh lời ổn định và rủi ro thấp.

* **Bài 10.9 \[Vận dụng\]:** Một nông trường thử nghiệm hai giống ngô giống A và giống B trên cùng điều kiện diện tích, cho năng suất trung bình như nhau là $65\text{ tạ/ha}$. Độ lệch chuẩn của giống A là $s_A = 3{,}2\text{ tạ/ha}$, giống B là $s_B = 6{,}5\text{ tạ/ha}$. Giống ngô nào có khả năng chống chịu điều kiện môi trường ổn định hơn? *Lời giải:* Giống A có độ lệch chuẩn nhỏ hơn đáng kể ($3{,}2 < 6{,}5$), cho thấy năng suất đồng đều qua các vụ, ít bị ảnh hưởng bởi biến động thời tiết hơn giống B.

* **Bài 10.10 \[Vận dụng\]:** Chứng minh công thức tính nhanh phương sai của mẫu số liệu ghép nhóm: $s^2 = \dfrac{1}{n} \sum_{i=1}^k n_i c_i^2 - \bar{x}^2$ từ định nghĩa gốc $s^2 = \dfrac{1}{n} \sum_{i=1}^k n_i (c_i - \bar{x})^2$. *Lời giải:* Khai triển $\sum n_i (c_i - \bar{x})^2 = \sum n_i (c_i^2 - 2c_i \bar{x} + \bar{x}^2) = \sum n_i c_i^2 - 2\bar{x} \sum n_i c_i + \bar{x}^2 \sum n_i$. Vì $\sum n_i = n$ và $\sum n_i c_i = n\bar{x}$, ta có $\sum n_i c_i^2 - 2n\bar{x}^2 + n\bar{x}^2 = \sum n_i c_i^2 - n\bar{x}^2$. Chia cho $n$ ta được công thức tính nhanh (đpcm).

# PHẦN 2. CHƯƠNG IV: NGUYÊN HÀM VÀ TÍCH PHÂN

## A. LÝ THUYẾT TRỌNG TÂM CHƯƠNG IV

### 1. Bài 11: Nguyên hàm

* **Định nghĩa:** Cho hàm số $f(x)$ xác định trên $K$. Hàm số $F(x)$ là nguyên hàm của $f(x)$ trên $K \Leftrightarrow F'(x) = f(x), \forall x \in K$. Họ nguyên hàm: $\int f(x)dx = F(x) + C$.

* **Bảng nguyên hàm cơ bản:**

  * $\int 0 dx = C$; $\int 1 dx = x + C$; $\int x^\alpha dx = \dfrac{x^{\alpha+1}}{\alpha+1} + C$ ($\alpha \ne -1$).

  * $\int \dfrac{1}{x} dx = \ln|x| + C$; $\int e^x dx = e^x + C$; $\int a^x dx = \dfrac{a^x}{\ln a} + C$.

  * $\int \cos x dx = \sin x + C$; $\int \sin x dx = -\cos x + C$; $\int \dfrac{1}{\cos^2 x} dx = \tan x + C$; $\int \dfrac{1}{\sin^2 x} dx = -\cot x + C$.

* **Phương pháp tính:**

  * Đổi biến số: $\int f(u(x)) u'(x) dx = \int f(u) du = F(u) + C$.

  * Từng phần: $\int u dv = uv - \int v du$ (thứ tự ưu tiên đặt $u$: "Nhất lô, nhì đa, tam lượng, tứ mũ").

### 2. Bài 12: Tích phân

* **Định nghĩa:** $\int_a^b f(x)dx = F(b) - F(a) = F(x)\Big|_a^b$.

* **Tính chất:** $\int_a^a = 0$; $\int_a^b = -\int_b^a$; $\int_a^b f = \int_a^c f + \int_c^b f$; tính tuyến tính $\int (k f + g) = k\int f + \int g$.

* **Phương pháp tính:** Đổi biến số (bắt buộc phải đổi cận!), tích phân từng phần: $\int_a^b u dv = (uv)\Big|_a^b - \int_a^b v du$.

### 3. Bài 13: Ứng dụng hình học của tích phân

* **Diện tích hình phẳng:**

  * Giới hạn bởi $y = f(x)$, $Ox$, $x = a, x = b$: $S = \int_a^b |f(x)|dx$.

  * Giới hạn bởi hai đường cong $y = f(x)$ và $y = g(x)$: $S = \int_a^b |f(x) - g(x)|dx$.

* **Thể tích vật thể:** $V = \int_a^b S(x)dx$ với $S(x)$ là diện tích thiết diện vuông góc trục $Ox$.

* **Thể tích khối tròn xoay quanh** $Ox$**:** $V = \pi \int_a^b [f(x)]^2 dx$.

## B. HỆ THỐNG 30 BÀI TẬP TỰ LUYỆN TỰ LUẬN CHƯƠNG IV (4 BIẾT – 3 HIỂU – 3 VẬN DỤNG)

### DẠNG 4.1: TÌM NGUYÊN HÀM CỦA HÀM SỐ (10 BÀI TỰ LUẬN)

* **Bài 11.1 \[Nhận biết\]:** Tìm họ nguyên hàm của hàm số $f(x) = 3x^2 - 4x + 5$. *Lời giải:* $\int (3x^2 - 4x + 5)dx = x^3 - 2x^2 + 5x + C$.

* **Bài 11.2 \[Nhận biết\]:** Tìm họ nguyên hàm của hàm số lượng giác $f(x) = \cos 2x - \sin x$. *Lời giải:* $\int (\cos 2x - \sin x)dx = \dfrac{1}{2}\sin 2x + \cos x + C$.

* **Bài 11.3 \[Nhận biết\]:** Tìm nguyên hàm $F(x)$ của hàm số $f(x) = e^x + 2x$ thỏa mãn $F(0) = 3$. *Lời giải:* $F(x) = e^x + x^2 + C$. $F(0) = 1 + 0 + C = 3 \Rightarrow C = 2$. Vậy $F(x) = e^x + x^2 + 2$.

* **Bài 11.4 \[Nhận biết\]:** Tìm họ nguyên hàm của hàm số phân thức $f(x) = \dfrac{1}{2x + 1}$ trên khoảng $(0; +\infty)$. *Lời giải:* $\int \dfrac{1}{2x + 1}dx = \dfrac{1}{2}\ln|2x + 1| + C = \dfrac{1}{2}\ln(2x + 1) + C$.

* **Bài 11.5 \[Thông hiểu\]:** Tìm họ nguyên hàm bằng phương pháp đổi biến số: $\int 2x(x^2 + 1)^4 dx$. *Lời giải:* Đặt $u = x^2 + 1 \Rightarrow du = 2x dx$. Ta có $\int u^4 du = \dfrac{u^5}{5} + C = \dfrac{(x^2 + 1)^5}{5} + C$.

* **Bài 11.6 \[Thông hiểu\]:** Tìm họ nguyên hàm bằng phương pháp từng phần: $\int x e^x dx$. *Lời giải:* Đặt $u = x \Rightarrow du = dx$; $dv = e^x dx \Rightarrow v = e^x$. $\int x e^x dx = x e^x - \int e^x dx = x e^x - e^x + C = (x - 1)e^x + C$.

* **Bài 11.7 \[Thông hiểu\]:** Tìm nguyên hàm của hàm số $f(x) = \dfrac{2x + 3}{x^2 + 3x - 4}$. *Lời giải:* Đặt $u = x^2 + 3x - 4 \Rightarrow du = (2x + 3)dx$. Nguyên hàm là $\int \dfrac{du}{u} = \ln|u| + C = \ln|x^2 + 3x - 4| + C$.

* **Bài 11.8 \[Vận dụng\]:** Tìm họ nguyên hàm của hàm số $f(x) = x \ln x$. *Lời giải:* Đặt $u = \ln x \Rightarrow du = \dfrac{1}{x}dx$; $dv = x dx \Rightarrow v = \dfrac{x^2}{2}$. $\int x\ln x dx = \dfrac{x^2}{2}\ln x - \int \dfrac{x^2}{2} \cdot \dfrac{1}{x}dx = \dfrac{x^2}{2}\ln x - \dfrac{x^2}{4} + C$.

* **Bài 11.9 \[Vận dụng\]:** Một chất điểm chuyển động với vận tốc $v(t) = 3t^2 - 6t + 2$ (m/s). Biết tại thời điểm $t = 0$, chất điểm ở vị trí có tọa độ $s(0) = 5\text{ m}$. Xác định phương trình chuyển động $s(t)$ của chất điểm. *Lời giải:* $s(t) = \int v(t)dt = t^3 - 3t^2 + 2t + C$. $s(0) = 5 \Rightarrow C = 5$. Vậy $s(t) = t^3 - 3t^2 + 2t + 5$ (m).

* **Bài 11.10 \[Vận dụng\]:** Cho hàm số $f(x)$ liên tục trên $\mathbb{R}$ thỏa mãn $f(x) + x f'(x) = 3x^2 + 2x$. Biết $f(1) = 2$, tìm hàm số $f(x)$. *Lời giải:* Nhận xét vế trái là $(x f(x))' = f(x) + x f'(x)$. Do đó $x f(x) = \int (3x^2 + 2x)dx = x^3 + x^2 + C$. Với $x = 1: 1 \cdot f(1) = 1 + 1 + C = 2 \Rightarrow C = 0$. Suy ra $f(x) = x^2 + x$.

### DẠNG 4.2: TÍNH TÍCH PHÂN XÁC ĐỊNH (10 BÀI TỰ LUẬN)

* **Bài 12.1 \[Nhận biết\]:** Tính tích phân cơ bản $I = \int_0^2 (3x^2 - 2x + 1)dx$. *Lời giải:* $I = (x^3 - x^2 + x)\Big|_0^2 = (8 - 4 + 2) - 0 = 6$.

* **Bài 12.2 \[Nhận biết\]:** Cho $\int_1^3 f(x)dx = 4$ và $\int_3^5 f(x)dx = -1$. Tính $\int_1^5 f(x)dx$. *Lời giải:* $\int_1^5 f(x)dx = \int_1^3 f(x)dx + \int_3^5 f(x)dx = 4 + (-1) = 3$.

* **Bài 12.3 \[Nhận biết\]:** Tính tích phân $I = \int_0^{\pi/2} \cos x dx$. *Lời giải:* $I = \sin x\Big|_0^{\pi/2} = \sin(\pi/2) - \sin 0 = 1 - 0 = 1$.

* **Bài 12.4 \[Nhận biết\]:** Tính tích phân $I = \int_1^e \dfrac{1}{x} dx$. *Lời giải:* $I = \ln|x|\Big|_1^e = \ln e - \ln 1 = 1 - 0 = 1$.

* **Bài 12.5 \[Thông hiểu\]:** Tính tích phân bằng phương pháp đổi biến số $I = \int_0^1 2x(x^2 + 1)^3 dx$. *Lời giải:* Đặt $u = x^2 + 1 \Rightarrow du = 2x dx$. Đổi cận: $x = 0 \Rightarrow u = 1; x = 1 \Rightarrow u = 2$. $I = \int_1^2 u^3 du = \dfrac{u^4}{4}\Big|_1^2 = \dfrac{16 - 1}{4} = \dfrac{15}{4}$.

* **Bài 12.6 \[Thông hiểu\]:** Tính tích phân từng phần $I = \int_0^1 (2x + 1)e^x dx$. *Lời giải:* Đặt $u = 2x + 1 \Rightarrow du = 2dx$; $dv = e^x dx \Rightarrow v = e^x$. $I = (2x + 1)e^x\Big|_0^1 - \int_0^1 2e^x dx = (3e - 1) - 2(e - 1) = e + 1$.

* **Bài 12.7 \[Thông hiểu\]:** Tính tích phân $I = \int_0^1 \dfrac{x}{x + 1} dx$. *Lời giải:* Biến đổi $\dfrac{x}{x + 1} = 1 - \dfrac{1}{x + 1}$. $I = (x - \ln|x + 1|)\Big|_0^1 = (1 - \ln 2) - (0 - \ln 1) = 1 - \ln 2$.

* **Bài 12.8 \[Vận dụng\]:** Tính tích phân $I = \int_1^e x \ln x dx$. *Lời giải:* Đặt $u = \ln x, dv = x dx \Rightarrow du = dx/x, v = x^2/2$. $I = \left(\dfrac{x^2}{2}\ln x\right)\Big|_1^e - \int_1^e \dfrac{x}{2}dx = \dfrac{e^2}{2} - \dfrac{x^2}{4}\Big|_1^e = \dfrac{e^2}{2} - \dfrac{e^2 - 1}{4} = \dfrac{e^2 + 1}{4}$.

* **Bài 12.9 \[Vận dụng\]:** Cho hàm số $f(x)$ liên tục trên $\mathbb{R}$ và $\int_0^4 f(x)dx = 8$. Tính $I = \int_0^2 x f(x^2) dx$. *Lời giải:* Đặt $t = x^2 \Rightarrow dt = 2x dx \Rightarrow x dx = dt/2$. Đổi cận: $x = 0 \Rightarrow t = 0; x = 2 \Rightarrow t = 4$. $I = \int_0^4 f(t) \dfrac{dt}{2} = \dfrac{1}{2} \int_0^4 f(t)dt = \dfrac{1}{2}(8) = 4$.

* **Bài 12.10 \[Vận dụng\]:** Cho $\int_0^1 \dfrac{2x + 1}{x^2 + 3x + 2} dx = a\ln 2 + b\ln 3$ ($a, b \in \mathbb{Z}$). Tìm giá trị của $a + b$. *Lời giải:* Phân tích $\dfrac{2x + 1}{(x + 1)(x + 2)} = \dfrac{-1}{x + 1} + \dfrac{3}{x + 2}$. Khi đó $I = [-\ln|x + 1| + 3\ln|x + 2|]\Big|_0^1 = (-\ln 2 + 3\ln 3) - (-\ln 1 + 3\ln 2) = 3\ln 3 - 4\ln 2$. Suy ra $a = -4, b = 3 \Rightarrow a + b = -1$.

### DẠNG 4.3: ỨNG DỤNG TÍCH PHÂN TÍNH DIỆN TÍCH VÀ THỂ TÍCH (10 BÀI TỰ LUẬN)

* **Bài 13.1 \[Nhận biết\]:** Tính diện tích hình phẳng giới hạn bởi đồ thị $y = x^2 - 2x$, trục hoành $y = 0$ và hai đường thẳng $x = 0, x = 2$. *Lời giải:* Trên đoạn $[0; 2]$, $x^2 - 2x \le 0$. $S = \int_0^2 -(x^2 - 2x)dx = \left(-\dfrac{x^3}{3} + x^2\right)\Big|_0^2 = -\dfrac{8}{3} + 4 = \dfrac{4}{3}$.

* **Bài 13.2 \[Nhận biết\]:** Viết công thức tính thể tích khối tròn xoay tạo thành khi quay hình phẳng giới hạn bởi đồ thị $y = \sqrt{x}$, trục hoành và hai đường thẳng $x = 1, x = 4$ quanh trục $Ox$. *Lời giải:* $V = \pi \int_1^4 (\sqrt{x})^2 dx = \pi \int_1^4 x dx = \pi \cdot \dfrac{x^2}{2}\Big|_1^4 = \pi \cdot \dfrac{16 - 1}{2} = \dfrac{15\pi}{2}$.

* **Bài 13.3 \[Nhận biết\]:** Tính diện tích hình phẳng giới hạn bởi đường cong $y = e^x$, trục hoành $y = 0$ và hai đường thẳng $x = 0, x = 1$. *Lời giải:* $S = \int_0^1 e^x dx = e^x\Big|_0^1 = e - 1$.

* **Bài 13.4 \[Nhận biết\]:** Tính thể tích vật thể nằm giữa hai mặt phẳng $x = 0$ và $x = 3$, biết diện tích thiết diện vuông góc trục $Ox$ tại hoành độ $x$ là $S(x) = 2x + 1$. *Lời giải:* $V = \int_0^3 S(x)dx = \int_0^3 (2x + 1)dx = (x^2 + x)\Big|_0^3 = 9 + 3 = 12$.

* **Bài 13.5 \[Thông hiểu\]:** Tính diện tích hình phẳng giới hạn bởi parabol $y = x^2$ và đường thẳng $y = 2x$. *Lời giải:* Phương trình hoành độ giao điểm: $x^2 = 2x \Leftrightarrow x^2 - 2x = 0 \Leftrightarrow x = 0$ hoặc $x = 2$. $S = \int_0^2 |x^2 - 2x|dx = \int_0^2 (2x - x^2)dx = \left(x^2 - \dfrac{x^3}{3}\right)\Big|_0^2 = 4 - \dfrac{8}{3} = \dfrac{4}{3}$.

* **Bài 13.6 \[Thông hiểu\]:** Tính thể tích khối tròn xoay khi quay hình phẳng giới hạn bởi $y = \cos x$, trục hoành, $x = 0, x = \pi/2$ quanh trục $Ox$. *Lời giải:* $V = \pi \int_0^{\pi/2} \cos^2 x dx = \pi \int_0^{\pi/2} \dfrac{1 + \cos 2x}{2} dx = \dfrac{\pi}{2} \left(x + \dfrac{\sin 2x}{2}\right)\Big|_0^{\pi/2} = \dfrac{\pi}{2} \cdot \dfrac{\pi}{2} = \dfrac{\pi^2}{4}$.

* **Bài 13.7 \[Thông hiểu\]:** Tính diện tích hình phẳng giới hạn bởi hai đồ thị $y = x^3$ và $y = x$. *Lời giải:* Hoành độ giao điểm: $x^3 - x = 0 \Leftrightarrow x(x - 1)(x + 1) = 0 \Leftrightarrow x = -1, 0, 1$. $S = \int_{-1}^1 |x^3 - x|dx = 2\int_0^1 (x - x^3)dx = 2\left(\dfrac{x^2}{2} - \dfrac{x^4}{4}\right)\Big|_0^1 = 2\left(\dfrac{1}{2} - \dfrac{1}{4}\right) = \dfrac{1}{2}$.

* **Bài 13.8 \[Vận dụng\]:** Một cổng chào có hình dạng parabol $y = 4 - x^2$ (đơn vị: mét). Người ta muốn lắp đèn trang trí trên toàn bộ diện tích của cổng chắn bởi mặt đất ($y = 0$). Tính diện tích mặt bằng của cổng chào. *Lời giải:* Giao điểm với mặt đất $y = 0 \Leftrightarrow 4 - x^2 = 0 \Leftrightarrow x = \pm 2$. Diện tích cổng chào: $S = \int_{-2}^2 (4 - x^2)dx = 2\int_0^2 (4 - x^2)dx = 2\left(4x - \dfrac{x^3}{3}\right)\Big|_0^2 = 2\left(8 - \dfrac{8}{3}\right) = \dfrac{32}{3}\text{ m}^2 \approx 10{,}67\text{ m}^2$.

* **Bài 13.9 \[Vận dụng\]:** Một bồn chứa xăng dầu có dạng khối tròn xoay thu được khi quay hình phẳng giới hạn bởi đường cong $y = \sqrt{4 - x^2}$ và trục hoành ($0 \le x \le 2$) quanh trục $Ox$ (đơn vị mét). Tính thể tích của nửa khối cầu chứa xăng này. *Lời giải:* $V = \pi \int_0^2 (\sqrt{4 - x^2})^2 dx = \pi \int_0^2 (4 - x^2)dx = \pi\left(4x - \dfrac{x^3}{3}\right)\Big|_0^2 = \pi\left(8 - \dfrac{8}{3}\right) = \dfrac{16\pi}{3}\text{ m}^3 \approx 16{,}76\text{ m}^3$.

* **Bài 13.10 \[Vận dụng\]:** Tính diện tích hình phẳng giới hạn bởi parabol $y = x^2 - 4x + 3$ và hai tiếp tuyến của parabol đi qua điểm $A\left(\dfrac{3}{2}; -3\right)$. *Lời giải:* Viết PTTT đi qua $A$: $y = k\left(x - \dfrac{3}{2}\right) - 3$. Hệ điều kiện tiếp xúc cho 2 tiếp điểm $x_1 = 0, x_2 = 3$ với hai tiếp tuyến $d_1: y = -4x + 3$ và $d_2: y = 2x - 6$. Chia tích phân tại $x = 3/2$, tính tổng hai phần diện tích: $S = \int_0^{3/2} [(x^2 - 4x + 3) - (-4x + 3)]dx + \int_{3/2}^3 [(x^2 - 4x + 3) - (2x - 6)]dx = \dfrac{9}{8} + \dfrac{9}{8} = \dfrac{9}{4}$.

# PHẦN 3. CHƯƠNG V: PHƯƠNG PHÁP TỌA ĐỘ TRONG KHÔNG GIAN

## A. LÝ THUYẾT TRỌNG TÂM CHƯƠNG V

### 1. Bài 14: Phương trình mặt phẳng

* **Vectơ pháp tuyến (VTPT):** Vectơ $\vec{n} \ne \vec{0}$ vuông góc với mặt phẳng $(P)$.

* **Phương trình tổng quát:** $Ax + By + Cz + D = 0$ ($A^2 + B^2 + C^2 > 0$). VTPT là $\vec{n} = (A; B; C)$.

* **Mặt phẳng qua** $M_0(x_0; y_0; z_0)$ **có VTPT** $\vec{n} = (A; B; C)$**:** 

  $$
  A(x - x_0) + B(y - y_0) + C(z - z_0) = 0
  $$

* **Phương trình đoạn chắn:** Qua $A(a; 0; 0), B(0; b; 0), C(0; 0; c)$ là $\dfrac{x}{a} + \dfrac{y}{b} + \dfrac{z}{c} = 1$.

* **Khoảng cách từ điểm** $M_0(x_0; y_0; z_0)$ **đến mặt phẳng** $(P)$**:** 

  $$
  d(M_0, (P)) = \dfrac{|A x_0 + B y_0 + C z_0 + D|}{\sqrt{A^2 + B^2 + C^2}}
  $$

### 2. Bài 15: Phương trình đường thẳng trong không gian

* **Vectơ chỉ phương (VTCP):** Vectơ $\vec{u} \ne \vec{0}$ song song hoặc nằm trên đường thẳng $d$.

* **Phương trình tham số:** Đi qua $M_0(x_0; y_0; z_0)$ có VTCP $\vec{u} = (a; b; c)$: 

  $$
  \begin{cases} x = x_0 + at \\ y = y_0 + bt \\ z = z_0 + ct \end{cases} \quad (t \in \mathbb{R})
  $$

* **Phương trình chính tắc (khi** $a, b, c \ne 0$**):** $\dfrac{x - x_0}{a} = \dfrac{y - y_0}{b} = \dfrac{z - z_0}{c}$.

### 3. Bài 16: Công thức tính góc trong không gian

* **Góc giữa hai đường thẳng:** $\cos(d_1, d_2) = \dfrac{|\vec{u_1} \cdot \vec{u_2}|}{|\vec{u_1}| |\vec{u_2}|}$.

* **Góc giữa hai mặt phẳng:** $\cos((P), (Q)) = \dfrac{|\vec{n_1} \cdot \vec{n_2}|}{|\vec{n_1}| |\vec{n_2}|}$.

* **Góc giữa đường thẳng và mặt phẳng:** $\sin(d, (P)) = \dfrac{|\vec{u} \cdot \vec{n}|}{|\vec{u}| |\vec{n}|}$.

### 4. Bài 17: Phương trình mặt cầu

* **Dạng chính tắc:** Mặt cầu tâm $I(a; b; c)$ bán kính $R$: 

  $$
  (x - a)^2 + (y - b)^2 + (z - c)^2 = R^2
  $$

* **Dạng khai triển:** $x^2 + y^2 + z^2 - 2ax - 2by - 2cz + d = 0$ với điều kiện $a^2 + b^2 + c^2 - d > 0$ và bán kính $R = \sqrt{a^2 + b^2 + c^2 - d}$.

* **Vị trí tương đối với mặt phẳng** $(P)$**:**

  * $d(I, (P)) > R$: Mặt phẳng không cắt mặt cầu.

  * $d(I, (P)) = R$: Mặt phẳng tiếp xúc mặt cầu tại tiếp điểm $H$ (hình chiếu của $I$).

  * $d(I, (P)) < R$: Mặt phẳng cắt mặt cầu theo đường tròn có bán kính $r = \sqrt{R^2 - d^2}$.

## B. HỆ THỐNG 40 BÀI TẬP TỰ LUYỆN TỰ LUẬN CHƯƠNG V (4 DẠNG X 10 BÀI: 4 BIẾT – 3 HIỂU – 3 VẬN DỤNG)

### DẠNG 5.1: PHƯƠNG TRÌNH MẶT PHẲNG VÀ KHOẢNG CÁCH (10 BÀI TỰ LUẬN)

* **Bài 14.1 \[Nhận biết\]:** Viết phương trình mặt phẳng đi qua điểm $M(1; -2; 3)$ và có một vectơ pháp tuyến $\vec{n} = (2; -1; 4)$. *Lời giải:* $2(x - 1) - 1(y + 2) + 4(z - 3) = 0 \Leftrightarrow 2x - y + 4z - 16 = 0$.

* **Bài 14.2 \[Nhận biết\]:** Viết phương trình mặt phẳng đi qua ba điểm $A(2; 0; 0), B(0; -3; 0), C(0; 0; 4)$ theo phương trình đoạn chắn. *Lời giải:* $\dfrac{x}{2} + \dfrac{y}{-3} + \dfrac{z}{4} = 1 \Leftrightarrow 6x - 4y + 3z - 12 = 0$.

* **Bài 14.3 \[Nhận biết\]:** Tính khoảng cách từ điểm $M(1; 2; -1)$ đến mặt phẳng $(P): 2x - 2y + z + 5 = 0$. *Lời giải:* $d(M, (P)) = \dfrac{|2(1) - 2(2) + 1(-1) + 5|}{\sqrt{2^2 + (-2)^2 + 1^2}} = \dfrac{|2 - 4 - 1 + 5|}{\sqrt{9}} = \dfrac{2}{3}$.

* **Bài 14.4 \[Nhận biết\]:** Xác định vị trí tương đối của hai mặt phẳng $(P): 2x - y + 3z - 1 = 0$ và $(Q): 4x - 2y + 6z + 5 = 0$. *Lời giải:* Tỉ số hệ số: $\dfrac{4}{2} = \dfrac{-2}{-1} = \dfrac{6}{3} = 2 \ne \dfrac{5}{-1}$. Suy ra $(P) // (Q)$.

* **Bài 14.5 \[Thông hiểu\]:** Viết phương trình mặt phẳng trung trực của đoạn thẳng $AB$ với $A(1; 2; -1)$ và $B(3; 0; 1)$. *Lời giải:* Trung điểm $M(2; 1; 0)$. VTPT $\vec{n} = \vec{AB} = (2; -2; 2) \Rightarrow \vec{n_0} = (1; -1; 1)$. Phương trình: $1(x - 2) - 1(y - 1) + 1(z - 0) = 0 \Leftrightarrow x - y + z - 1 = 0$.

* **Bài 14.6 \[Thông hiểu\]:** Viết phương trình mặt phẳng đi qua điểm $A(1; 0; 2)$ và song song với mặt phẳng $(P): 3x - y + 2z - 5 = 0$. *Lời giải:* Mặt phẳng $(Q) // (P)$ có dạng $3x - y + 2z + D = 0$ ($D \ne -5$). Vì $A \in (Q): 3(1) - 0 + 2(2) + D = 0 \Rightarrow D = -7$. Phương trình: $3x - y + 2z - 7 = 0$.

* **Bài 14.7 \[Thông hiểu\]:** Viết phương trình mặt phẳng đi qua ba điểm $A(1; 1; 1), B(2; 3; 0), C(0; 2; 3)$. *Lời giải:* $\vec{AB} = (1; 2; -1), \vec{AC} = (-1; 1; 2) \Rightarrow \vec{n} = [\vec{AB}, \vec{AC}] = (5; -1; 3)$. Phương trình qua $A$: $5(x - 1) - 1(y - 1) + 3(z - 1) = 0 \Leftrightarrow 5x - y + 3z - 7 = 0$.

* **Bài 14.8 \[Vận dụng\]:** Tìm tất cả các giá trị của tham số $m$ để khoảng cách từ gốc tọa độ $O$ đến mặt phẳng $(P): 2x - 2y + z + m = 0$ bằng $2$. *Lời giải:* $d(O, (P)) = \dfrac{|m|}{\sqrt{4 + 4 + 1}} = \dfrac{|m|}{3} = 2 \Leftrightarrow |m| = 6 \Leftrightarrow m = \pm 6$.

* **Bài 14.9 \[Vận dụng\]:** Viết phương trình mặt phẳng $(P)$ chứa trục $Ox$ và vuông góc với mặt phẳng $(Q): x - 2y + z - 3 = 0$. *Lời giải:* Mặt phẳng $(P)$ chứa $Ox$ có VTCP $\vec{i} = (1; 0; 0)$ và vuông góc $(Q)$ có $\vec{n_Q} = (1; -2; 1)$. VTPT của $(P)$ là $[\vec{i}, \vec{n_Q}] = (0; -1; -2) \Rightarrow \vec{n} = (0; 1; 2)$. Điểm $O(0; 0; 0) \in (P) \Rightarrow y + 2z = 0$.

* **Bài 14.10 \[Vận dụng\]:** Trong không gian $Oxyz$, một mái nhà phẳng có phương trình $(P): 2x + 2y - z + 12 = 0$. Một ăng-ten được đặt tại điểm $A(3; 4; 5)$. Hãy tính khoảng cách ngắn nhất từ đỉnh ăng-ten đến mái nhà và tìm tọa độ hình chiếu vuông góc của $A$ lên mái nhà. *Lời giải:* $d(A, (P)) = \dfrac{|2(3) + 2(4) - 5 + 12|}{\sqrt{4 + 4 + 1}} = \dfrac{|21|}{3} = 7\text{ m}$. Đường thẳng qua $A$ vuông góc $(P)$ có phương trình $\begin{cases} x = 3 + 2t \\ y = 4 + 2t \\ z = 5 - t \end{cases}$. Thay vào $(P): 2(3+2t) + 2(4+2t) - (5-t) + 12 = 0 \Leftrightarrow 9t + 21 = 0 \Leftrightarrow t = -\dfrac{7}{3}$. Hình chiếu $H\left(-\dfrac{5}{3}; -\dfrac{2}{3}; \dfrac{22}{3}\right)$.

### DẠNG 5.2: PHƯƠNG TRÌNH ĐƯỜNG THẲNG TRONG KHÔNG GIAN (10 BÀI TỰ LUẬN)

* **Bài 15.1 \[Nhận biết\]:** Viết phương trình tham số của đường thẳng $d$ đi qua điểm $M(1; -2; 4)$ và có VTCP $\vec{u} = (2; 3; -1)$. *Lời giải:* $\begin{cases} x = 1 + 2t \\ y = -2 + 3t \\ z = 4 - t \end{cases} (t \in \mathbb{R})$.

* **Bài 15.2 \[Nhận biết\]:** Viết phương trình chính tắc của đường thẳng đi qua hai điểm $A(2; 1; 0)$ và $B(4; -1; 3)$. *Lời giải:* VTCP $\vec{AB} = (2; -2; 3)$. Phương trình chính tắc: $\dfrac{x - 2}{2} = \dfrac{y - 1}{-2} = \dfrac{z}{3}$.

* **Bài 15.3 \[Nhận biết\]:** Tìm tọa độ một điểm thuộc đường thẳng và một vectơ chỉ phương của đường thẳng $d: \dfrac{x + 1}{3} = \dfrac{y - 2}{-4} = \dfrac{z - 5}{1}$. *Lời giải:* Điểm $M(-1; 2; 5) \in d$ và VTCP $\vec{u} = (3; -4; 1)$.

* **Bài 15.4 \[Nhận biết\]:** Xét vị trí tương đối giữa đường thẳng $d: \begin{cases} x = 1 + t \\ y = 2 - t \\ z = 3 + 2t \end{cases}$ và mặt phẳng $(P): 2x + 2y - z + 1 = 0$. *Lời giải:* VTCP $\vec{u} = (1; -1; 2)$, VTPT $\vec{n} = (2; 2; -1)$. Ta có $\vec{u} \cdot \vec{n} = 1(2) - 1(2) + 2(-1) = -2 \ne 0$. Do đó đường thẳng cắt mặt phẳng.

* **Bài 15.5 \[Thông hiểu\]:** Viết phương trình đường thẳng $\Delta$ đi qua điểm $A(1; 0; -2)$ và vuông góc với mặt phẳng $(P): 2x - 3y + z - 4 = 0$. *Lời giải:* Vì $\Delta \perp (P)$ nên VTCP của $\Delta$ là $\vec{u} = \vec{n_P} = (2; -3; 1)$. Phương trình: $\begin{cases} x = 1 + 2t \\ y = -3t \\ z = -2 + t \end{cases}$.

* **Bài 15.6 \[Thông hiểu\]:** Tìm tọa độ giao điểm của đường thẳng $d: \dfrac{x - 1}{2} = \dfrac{y + 2}{-1} = \dfrac{z}{1}$ và mặt phẳng $(P): x + y - 2z + 3 = 0$. *Lời giải:* Phương trình tham số: $x = 1 + 2t, y = -2 - t, z = t$. Thay vào $(P): (1 + 2t) + (-2 - t) - 2t + 3 = 0 \Leftrightarrow -t + 2 = 0 \Leftrightarrow t = 2$. Giao điểm là $M(5; -4; 2)$.

* **Bài 15.7 \[Thông hiểu\]:** Chứng minh hai đường thẳng sau chéo nhau: $d_1: \begin{cases} x = 1 + t \\ y = 2 \\ z = -t \end{cases}$ và $d_2: \begin{cases} x = 2 \\ y = 1 - s \\ z = 3 + s \end{cases}$. *Lời giải:* VTCP $\vec{u_1} = (1; 0; -1), \vec{u_2} = (0; -1; 1) \Rightarrow [\vec{u_1}, \vec{u_2}] = (-1; -1; -1) \ne \vec{0}$ (không cùng phương). Lấy $M_1(1; 2; 0) \in d_1, M_2(2; 1; 3) \in d_2 \Rightarrow \vec{M_1 M_2} = (1; -1; 3)$. Tích hỗn tạp $[\vec{u_1}, \vec{u_2}] \cdot \vec{M_1 M_2} = -1(1) - 1(-1) - 1(3) = -3 \ne 0$. Vậy hai đường thẳng chéo nhau.

* **Bài 15.8 \[Vận dụng\]:** Viết phương trình hình chiếu vuông góc của đường thẳng $d: \dfrac{x - 1}{2} = \dfrac{y + 1}{1} = \dfrac{z - 2}{1}$ lên mặt phẳng tọa độ $(Oxy)$. *Lời giải:* Mặt phẳng $(P)$ chứa $d$ và vuông góc $(Oxy)$ có VTPT là $[\vec{u_d}, \vec{k}] = [(2; 1; 1), (0; 0; 1)] = (1; -2; 0)$. Điểm $M(1; -1; 2) \in (P) \Rightarrow 1(x - 1) - 2(y + 1) = 0 \Leftrightarrow x - 2y - 3 = 0$. Hình chiếu $d'$ là giao tuyến của $x - 2y - 3 = 0$ và $z = 0$.

* **Bài 15.9 \[Vận dụng\]:** Tìm khoảng cách giữa hai đường thẳng song song $d_1: \dfrac{x - 1}{1} = \dfrac{y}{2} = \dfrac{z + 1}{-1}$ và $d_2: \dfrac{x + 2}{1} = \dfrac{y - 1}{2} = \dfrac{z}{-1}$. *Lời giải:* VTCP chung $\vec{u} = (1; 2; -1)$. Điểm $M_1(1; 0; -1) \in d_1$ và $M_2(-2; 1; 0) \in d_2 \Rightarrow \vec{M_1 M_2} = (-3; 1; 1)$. Tích có hướng $[\vec{M_1 M_2}, \vec{u}] = (-3; -2; -7)$. Khoảng cách $d = \dfrac{|[\vec{M_1 M_2}, \vec{u}]|}{|\vec{u}|} = \dfrac{\sqrt{9 + 4 + 49}}{\sqrt{1 + 4 + 1}} = \dfrac{\sqrt{62}}{\sqrt{6}} = \dfrac{\sqrt{93}}{3}$.

* **Bài 15.10 \[Vận dụng\]:** Một tuyến cáp treo di chuyển theo đường thẳng $d: \begin{cases} x = 200 + 3t \\ y = 100 + 4t \\ z = 50 + t \end{cases}$ ($t$ tính bằng giây, tọa độ tính bằng mét). Một trạm phát sóng đặt tại điểm $S(200; 100; 150)$. Xác định thời điểm $t$ mà cabin cáp treo ở gần trạm phát sóng nhất và khoảng cách ngắn nhất đó. *Lời giải:* Cabin tại điểm $M(200+3t; 100+4t; 50+t)$. $\vec{SM} = (3t; 4t; t - 100)$. $SM^2 = 9t^2 + 16t^2 + (t - 100)^2 = 26t^2 - 200t + 10000$. Đạo hàm: $52t - 200 = 0 \Leftrightarrow t = \dfrac{200}{52} = \dfrac{50}{13}\text{ s} \approx 3{,}85\text{ s}$. Khoảng cách ngắn nhất $SM_{\min} = \sqrt{10000 - \dfrac{40000}{104}} \approx 98{,}06\text{ m}$.

### DẠNG 5.3: CÔNG THỨC TÍNH GÓC TRONG KHÔNG GIAN (10 BÀI TỰ LUẬN)

* **Bài 16.1 \[Nhận biết\]:** Tính cosin của góc giữa hai đường thẳng có VTCP lần lượt là $\vec{u_1} = (1; 2; -2)$ và $\vec{u_2} = (2; -1; 0)$. *Lời giải:* $\cos(d_1, d_2) = \dfrac{|1(2) + 2(-1) - 2(0)|}{\sqrt{1 + 4 + 4} \sqrt{4 + 1 + 0}} = \dfrac{0}{3\sqrt{5}} = 0 \Rightarrow$ Góc bằng $90^\circ$.

* **Bài 16.2 \[Nhận biết\]:** Tính cosin của góc giữa hai mặt phẳng $(P): x + y - 1 = 0$ và $(Q): y + z + 2 = 0$. *Lời giải:* $\vec{n_1} = (1; 1; 0), \vec{n_2} = (0; 1; 1)$. $\cos((P), (Q)) = \dfrac{|1(0) + 1(1) + 0(1)|}{\sqrt{2} \sqrt{2}} = \dfrac{1}{2} \Rightarrow$ Góc bằng $60^\circ$.

* **Bài 16.3 \[Nhận biết\]:** Nêu công thức tính sin của góc giữa đường thẳng $d$ có VTCP $\vec{u}$ và mặt phẳng $(P)$ có VTPT $\vec{n}$. *Lời giải:* $\sin(d, (P)) = \dfrac{|\vec{u} \cdot \vec{n}|}{|\vec{u}| |\vec{n}|}$.

* **Bài 16.4 \[Nhận biết\]:** Tính sin của góc giữa đường thẳng có VTCP $\vec{u} = (0; 0; 1)$ và mặt phẳng $(Oxy)$. *Lời giải:* $(Oxy)$ có $\vec{n} = (0; 0; 1)$. $\sin = \dfrac{|1|}{1 \cdot 1} = 1 \Rightarrow$ Góc bằng $90^\circ$.

* **Bài 16.5 \[Thông hiểu\]:** Tính góc giữa đường thẳng $d: \dfrac{x - 1}{1} = \dfrac{y}{1} = \dfrac{z + 2}{\sqrt{2}}$ và mặt phẳng $(P): x - y + \sqrt{2}z - 1 = 0$. *Lời giải:* $\vec{u} = (1; 1; \sqrt{2}), \vec{n} = (1; -1; \sqrt{2})$. $\vec{u} \cdot \vec{n} = 1(1) + 1(-1) + \sqrt{2}(\sqrt{2}) = 2$. $|\vec{u}| = \sqrt{1 + 1 + 2} = 2, |\vec{n}| = 2$. $\sin \alpha = \dfrac{|2|}{2 \cdot 2} = \dfrac{1}{2} \Rightarrow \alpha = 30^\circ$.

* **Bài 16.6 \[Thông hiểu\]:** Cho hai mặt phẳng $(P): 2x - y + 2z - 1 = 0$ và $(Q): x + 2y - 2z + 3 = 0$. Tính số đo góc giữa $(P)$ và $(Q)$. *Lời giải:* $\vec{n_1} = (2; -1; 2), \vec{n_2} = (1; 2; -2)$. $\vec{n_1} \cdot \vec{n_2} = 2(1) - 1(2) + 2(-2) = -4$. $|\vec{n_1}| = 3, |\vec{n_2}| = 3$. $\cos \phi = \dfrac{|-4|}{3 \cdot 3} = \dfrac{4}{9} \Rightarrow \phi = \arccos(4/9) \approx 63{,}6^\circ$.

* **Bài 16.7 \[Thông hiểu\]:** Tìm tham số $m$ để góc giữa hai vectơ $\vec{u} = (1; m; 1)$ và $\vec{v} = (2; 1; -1)$ bằng $90^\circ$. *Lời giải:* $\vec{u} \perp \vec{v} \Leftrightarrow 1(2) + m(1) + 1(-1) = 0 \Leftrightarrow m + 1 = 0 \Leftrightarrow m = -1$.

* **Bài 16.8 \[Vận dụng\]:** Cho hình chóp $S.ABC$ có $SA \perp (ABC)$, đáy $ABC$ vuông cân tại $B$ với $AB = SA = a$. Gắn hệ trục tọa độ $Oxyz$ và tính góc giữa đường thẳng $SB$ và mặt phẳng $(SAC)$. *Lời giải:* Chọn $B(0; 0; 0), A(a; 0; 0), C(0; a; 0), S(a; 0; a)$. $\vec{SB} = (-a; 0; -a) \Rightarrow \vec{u} = (1; 0; 1)$. Mặt phẳng $(SAC)$ qua $A(a; 0; 0)$ có cặp VTCP $\vec{AC} = (-a; a; 0)$ và $\vec{AS} = (0; 0; a) \Rightarrow \vec{n} = (1; 1; 0)$. $\sin \alpha = \dfrac{|1(1) + 0(1) + 1(0)|}{\sqrt{2} \sqrt{2}} = \dfrac{1}{2} \Rightarrow \alpha = 30^\circ$.

* **Bài 16.9 \[Vận dụng\]:** Hai máy bay di chuyển trên hai đường bay thẳng: máy bay thứ nhất theo hướng $\vec{u_1} = (3; 4; 0)$, máy bay thứ hai theo hướng $\vec{u_2} = (0; 5; 12)$. Tính góc tạo bởi hai đường bay. *Lời giải:* $|\vec{u_1}| = 5, |\vec{u_2}| = 13$. Tích vô hướng $\vec{u_1} \cdot \vec{u_2} = 3(0) + 4(5) + 0(12) = 20$. $\cos \theta = \dfrac{20}{5 \cdot 13} = \dfrac{4}{13} \approx 0{,}3077 \Rightarrow \theta \approx 72^\circ$.

* **Bài 16.10 \[Vận dụng\]:** Tìm tham số $m$ để góc giữa đường thẳng $d: \dfrac{x}{1} = \dfrac{y - 1}{2} = \dfrac{z + 1}{-1}$ và mặt phẳng $(P): mx + y - z + 2 = 0$ bằng $30^\circ$. *Lời giải:* $\vec{u} = (1; 2; -1), \vec{n} = (m; 1; -1)$. $\sin 30^\circ = \dfrac{1}{2} = \dfrac{|m + 2 + 1|}{\sqrt{6} \sqrt{m^2 + 2}} \Leftrightarrow \sqrt{6(m^2 + 2)} = 2|m + 3| \Leftrightarrow 6(m^2 + 2) = 4(m^2 + 6m + 9) \Leftrightarrow 2m^2 - 24m - 24 = 0 \Leftrightarrow m^2 - 12m - 12 = 0 \Leftrightarrow m = 6 \pm 4\sqrt{3}$.

### DẠNG 5.4: PHƯƠNG TRÌNH MẶT CẦU VÀ VỊ TRÍ TƯƠNG ĐỐI (10 BÀI TỰ LUẬN)

* **Bài 17.1 \[Nhận biết\]:** Viết phương trình mặt cầu tâm $I(1; -2; 3)$ bán kính $R = 4$. *Lời giải:* $(x - 1)^2 + (y + 2)^2 + (z - 3)^2 = 16$.

* **Bài 17.2 \[Nhận biết\]:** Xác định tọa độ tâm $I$ và bán kính $R$ của mặt cầu $(S): x^2 + y^2 + z^2 - 4x + 6y - 2z - 2 = 0$. *Lời giải:* $a = 2, b = -3, c = 1, d = -2$. $a^2 + b^2 + c^2 - d = 4 + 9 + 1 + 2 = 16 > 0$. Tâm $I(2; -3; 1)$, bán kính $R = \sqrt{16} = 4$.

* **Bài 17.3 \[Nhận biết\]:** Viết phương trình mặt cầu đường kính $AB$ với $A(1; 3; -1)$ và $B(3; 1; 1)$. *Lời giải:* Tâm $I(2; 2; 0)$ là trung điểm $AB$. Bán kính $R = AB/2 = \dfrac{\sqrt{4 + 4 + 4}}{2} = \dfrac{2\sqrt{3}}{2} = \sqrt{3}$. Phương trình: $(x - 2)^2 + (y - 2)^2 + z^2 = 3$.

* **Bài 17.4 \[Nhận biết\]:** Xét vị trí tương đối giữa mặt cầu $(S): x^2 + y^2 + z^2 = 9$ và mặt phẳng $(P): 2x - 2y + z + 9 = 0$. *Lời giải:* Mặt cầu tâm $O(0; 0; 0), R = 3$. $d(O, (P)) = \dfrac{|9|}{\sqrt{4 + 4 + 1}} = \dfrac{9}{3} = 3 = R$. Do đó $(P)$ tiếp xúc với mặt cầu $(S)$.

* **Bài 17.5 \[Thông hiểu\]:** Viết phương trình mặt cầu có tâm $I(2; 1; -3)$ và tiếp xúc với mặt phẳng tọa độ $(Oxy)$. *Lời giải:* Bán kính bằng khoảng cách từ $I$ đến $(Oxy)$: $R = |z_I| = |-3| = 3$. Phương trình: $(x - 2)^2 + (y - 1)^2 + (z + 3)^2 = 9$.

* **Bài 17.6 \[Thông hiểu\]:** Mặt phẳng $(P): x + 2y - 2z + 1 = 0$ cắt mặt cầu $(S): (x - 1)^2 + (y + 1)^2 + (z - 2)^2 = 25$ theo một đường tròn. Tính bán kính $r$ của đường tròn thiết diện đó. *Lời giải:* Tâm $I(1; -1; 2)$, bán kính $R = 5$. $d(I, (P)) = \dfrac{|1 + 2(-1) - 2(2) + 1|}{\sqrt{1 + 4 + 4}} = \dfrac{|-4|}{3} = \dfrac{4}{3}$. Bán kính đường tròn $r = \sqrt{R^2 - d^2} = \sqrt{25 - \dfrac{16}{9}} = \sqrt{\dfrac{209}{9}} = \dfrac{\sqrt{209}}{3}$.

* **Bài 17.7 \[Thông hiểu\]:** Tìm tất cả các giá trị của tham số $m$ để phương trình $x^2 + y^2 + z^2 - 2x + 4y - 6z + m = 0$ là phương trình của một mặt cầu. *Lời giải:* $a = 1, b = -2, c = 3$. Điều kiện: $a^2 + b^2 + c^2 - m > 0 \Leftrightarrow 1 + 4 + 9 - m > 0 \Leftrightarrow 14 - m > 0 \Leftrightarrow m < 14$.

* **Bài 17.8 \[Vận dụng\]:** Viết phương trình mặt phẳng tiếp xúc với mặt cầu $(S): (x - 1)^2 + (y - 2)^2 + (z + 1)^2 = 9$ tại điểm $M(2; 4; 1)$. *Lời giải:* Tâm $I(1; 2; -1)$. Điểm $M(2; 4; 1) \in (S)$. Tiếp diện tại $M$ có VTPT là $\vec{IM} = (1; 2; 2)$. Phương trình tiếp diện: $1(x - 2) + 2(y - 4) + 2(z - 1) = 0 \Leftrightarrow x + 2y + 2z - 12 = 0$.

* **Bài 17.9 \[Vận dụng\]:** Một trạm rada không lưu phát sóng quét trong một quả cầu bán kính $R = 100\text{ km}$ có tâm đặt tại $O(0; 0; 0)$. Một máy bay đang bay theo đường thẳng $d: \begin{cases} x = 120 + 3t \\ y = 80 - 4t \\ z = 10 \end{cases}$. Hãy xác định thời gian mà máy bay nằm trong vùng phát hiện của rada nếu vận tốc máy bay là $10\text{ km/phút}$. *Lời giải:* Khoảng cách từ $M(t)$ đến $O$: $x^2 + y^2 + z^2 \le 100^2$. Thay tọa độ giải bất phương trình bậc hai tìm đoạn thời gian $[t_1; t_2]$, tính độ dài quãng đường trong cầu và chia cho vận tốc để tìm thời gian bay trong vùng rada.

* **Bài 17.10 \[Vận dụng\]:** Cho mặt cầu $(S): (x - 1)^2 + (y + 2)^2 + (z - 3)^2 = 25$ và điểm $A(4; 2; 3)$. Tìm giá trị lớn nhất và giá trị nhỏ nhất của khoảng cách từ điểm $A$ đến một điểm $M$ bất kì thuộc mặt cầu $(S)$. *Lời giải:* Tâm $I(1; -2; 3), R = 5$. Khoảng cách $IA = \sqrt{(4 - 1)^2 + (2 + 2)^2 + (3 - 3)^2} = \sqrt{9 + 16 + 0} = 5 = R$. Vì $IA = R$ nên $A$ nằm trên mặt cầu. Do đó khoảng cách nhỏ nhất $AM_{\min} = 0$ (khi $M \equiv A$), khoảng cách lớn nhất $AM_{\max} = 2R = 10$ (khi $M$ đối xứng với $A$ qua tâm $I$).

# PHẦN 4. CHƯƠNG VI: XÁC SUẤT CÓ ĐIỀU KIỆN

## A. LÝ THUYẾT TRỌNG TÂM CHƯƠNG VI

### 1. Bài 18: Xác suất có điều kiện

* **Định nghĩa:** Xác suất của biến cố $A$ với điều kiện biến cố $B$ đã xảy ra (với $P(B) > 0$) được kí hiệu là $P(A|B)$ và tính bởi: 

  $$
  P(A|B) = \dfrac{P(AB)}{P(B)}
  $$

* **Công thức nhân xác suất:** 

  $$
  P(AB) = P(B) \cdot P(A|B) = P(A) \cdot P(B|A)
  $$

* **Tính độc lập:** Hai biến cố $A, B$ độc lập khi $P(A|B) = P(A)$ (hay $P(AB) = P(A)P(B)$).

### 2. Bài 19: Công thức xác suất toàn phần và công thức Bayes

* **Hệ biến cố đầy đủ:** Các biến cố $B_1, B_2, \dots, B_n$ tạo thành hệ đầy đủ nếu chúng đôi một xung khắc ($B_i \cap B_j = \emptyset$) và $B_1 \cup B_2 \cup \dots \cup B_n = \Omega$.

* **Công thức xác suất toàn phần:** Với mọi biến cố $A$: 

  $$
  P(A) = \sum_{i=1}^n P(B_i) \cdot P(A|B_i)
  $$

* **Công thức Bayes:** Với $P(A) > 0$: 

  $$
  P(B_k|A) = \dfrac{P(B_k) \cdot P(A|B_k)}{P(A)} = \dfrac{P(B_k) \cdot P(A|B_k)}{\sum_{i=1}^n P(B_i) \cdot P(A|B_i)}
  $$

* **Ý nghĩa thực tế:** Cập nhật xác suất tiên nghiệm $P(B_k)$ thành xác suất hậu nghiệm $P(B_k|A)$ khi có thêm bằng chứng (dữ liệu kiểm tra, kết quả xét nghiệm).

## B. HỆ THỐNG 20 BÀI TẬP TỰ LUYỆN TỰ LUẬN CHƯƠNG VI (2 DẠNG X 10 BÀI: 4 BIẾT – 3 HIỂU – 3 VẬN DỤNG)

### DẠNG 6.1: XÁC SUẤT CÓ ĐIỀU KIỆN VÀ CÔNG THỨC NHÂN (10 BÀI TỰ LUẬN)

* **Bài 18.1 \[Nhận biết\]:** Cho $P(A) = 0{,}6; P(B) = 0{,}5; P(AB) = 0{,}3$. Tính xác suất có điều kiện $P(A|B)$ và $P(B|A)$. *Lời giải:* $P(A|B) = \dfrac{P(AB)}{P(B)} = \dfrac{0{,}3}{0{,}5} = 0{,}6$. $P(B|A) = \dfrac{P(AB)}{P(A)} = \dfrac{0{,}3}{0{,}6} = 0{,}5$.

* **Bài 18.2 \[Nhận biết\]:** Gieo một con xúc xắc cân đối. Biết rằng số chấm xuất hiện là số chẵn, tính xác suất để số chấm xuất hiện là $2$. *Lời giải:* Không gian biến cố $B = \{2; 4; 6\} \Rightarrow n(B) = 3$. Biến cố $A = \{2\} \Rightarrow P(A|B) = 1/3$.

* **Bài 18.3 \[Nhận biết\]:** Phát biểu công thức nhân xác suất cho hai biến cố bất kì $A$ và $B$. *Lời giải:* $P(AB) = P(A) \cdot P(B|A) = P(B) \cdot P(A|B)$.

* **Bài 18.4 \[Nhận biết\]:** Một hộp có 6 quả cầu đỏ và 4 quả cầu xanh. Rút ngẫu nhiên không hoàn lại 2 quả cầu. Tính xác suất để quả thứ hai màu đỏ biết quả thứ nhất màu đỏ. *Lời giải:* Sau khi rút 1 quả đỏ, hộp còn 9 quả (5 đỏ, 4 xanh). Xác suất quả thứ hai màu đỏ là $5/9$.

* **Bài 18.5 \[Thông hiểu\]:** Trong một trường THPT, tỉ lệ học sinh thích môn Toán là $60\%$, thích môn Lý là $50\%$, thích cả hai môn là $35\%$. Chọn ngẫu nhiên 1 học sinh, biết bạn này thích môn Toán, tính xác suất để bạn đó thích cả môn Lý. *Lời giải:* $P(L|T) = \dfrac{P(TL)}{P(T)} = \dfrac{0{,}35}{0{,}60} = \dfrac{7}{12} \approx 58{,}33\%$.

* **Bài 18.6 \[Thông hiểu\]:** Một hộp có 5 bi trắng và 3 bi đen. Rút lần lượt 2 viên bi không hoàn lại. Tính xác suất để cả 2 viên bi đều là màu trắng. *Lời giải:* $P(T_1 T_2) = P(T_1) \cdot P(T_2|T_1) = \dfrac{5}{8} \cdot \dfrac{4}{7} = \dfrac{20}{56} = \dfrac{5}{14}$.

* **Bài 18.7 \[Thông hiểu\]:** Cho hai biến cố $A$ và $B$ thỏa mãn $P(A) = 0{,}4; P(B) = 0{,}5$ và $A, B$ độc lập. Tính $P(A|B)$ và $P(AB)$. *Lời giải:* Vì $A, B$ độc lập nên $P(A|B) = P(A) = 0{,}4$. $P(AB) = P(A)P(B) = 0{,}4 \cdot 0{,}5 = 0{,}2$.

* **Bài 18.8 \[Vận dụng\]:** Một người bắn 2 phát súng độc lập vào bia với xác suất bắn trúng mỗi phát là $0{,}7$. Biết rằng có ít nhất 1 phát bắn trúng bia, tính xác suất để phát thứ nhất bắn trúng bia. *Lời giải:* Gọi $A$: "Phát 1 trúng" ($P(A) = 0{,}7$), $B$: "Có ít nhất 1 phát trúng". Biến cố đối $\bar{B}$: "Cả 2 trúng trượt" $\Rightarrow P(\bar{B}) = 0{,}3 \cdot 0{,}3 = 0{,}09 \Rightarrow P(B) = 0{,}91$. Ta có $AB = A$ (nếu phát 1 trúng thì đương nhiên có ít nhất 1 phát trúng). Suy ra $P(A|B) = \dfrac{P(AB)}{P(B)} = \dfrac{0{,}7}{0{,}91} = \dfrac{70}{91} = \dfrac{10}{13} \approx 0{,}769$.

* **Bài 18.9 \[Vận dụng\]:** Tại một ngã tư, xác suất một chiếc xe rẽ trái là $0{,}3$, rẽ phải là $0{,}2$, đi thẳng là $0{,}5$. Biết rằng nếu xe rẽ trái thì xác suất gây ùn tắc là $0{,}4$, rẽ phải là $0{,}1$, đi thẳng là $0{,}05$. Vẽ sơ đồ hình cây và tính xác suất một chiếc xe ngẫu nhiên gây ra ùn tắc giao thông. *Lời giải:* Áp dụng công thức nhân và sơ đồ cây: $P(\text{Ùn tắc}) = 0{,}3(0{,}4) + 0{,}2(0{,}1) + 0{,}5(0{,}05) = 0{,}12 + 0{,}02 + 0{,}025 = 0{,}165 = 16{,}5\%$.

* **Bài 18.10 \[Vận dụng\]:** Kiểm tra hai dây chuyền sản xuất: Dây chuyền I cung cấp $60\%$ sản phẩm, Dây chuyền II cung cấp $40\%$. Tỉ lệ phế phẩm của Dây chuyền I là $2\%$, của Dây chuyền II là $3\%$. Chọn ngẫu nhiên một sản phẩm, tính xác suất để sản phẩm đó là chính phẩm. *Lời giải:* $P(\text{Phế phẩm}) = 0{,}6(0{,}02) + 0{,}4(0{,}03) = 0{,}012 + 0{,}012 = 0{,}024$. Xác suất chính phẩm là $1 - 0{,}024 = 0{,}976 = 97{,}6\%$.

### DẠNG 6.2: CÔNG THỨC XÁC SUẤT TOÀN PHẦN VÀ CÔNG THỨC BAYES (10 BÀI TỰ LUẬN)

* **Bài 19.1 \[Nhận biết\]:** Phát biểu công thức xác suất toàn phần đối với hệ hai biến cố đầy đủ $B$ và $\bar{B}$. *Lời giải:* $P(A) = P(B) \cdot P(A|B) + P(\bar{B}) \cdot P(A|\bar{B})$.

* **Bài 19.2 \[Nhận biết\]:** Viết công thức Bayes tính $P(B|A)$ khi biết $P(B), P(\bar{B}), P(A|B), P(A|\bar{B})$. *Lời giải:* $P(B|A) = \dfrac{P(B)P(A|B)}{P(B)P(A|B) + P(\bar{B})P(A|\bar{B})}$.

* **Bài 19.3 \[Nhận biết\]:** Giải thích ý nghĩa của "xác suất tiên nghiệm" và "xác suất hậu nghiệm" trong công thức Bayes. *Lời giải:* Xác suất tiên nghiệm $P(B)$ là xác suất ban đầu khi chưa có thông tin kiểm định; xác suất hậu nghiệm $P(B|A)$ là xác suất được cập nhật sau khi đã quan sát thấy biến cố $A$ xảy ra.

* **Bài 19.4 \[Nhận biết\]:** Cho $P(B_1) = 0{,}4; P(B_2) = 0{,}6$ là hệ đầy đủ. Biết $P(A|B_1) = 0{,}1$ và $P(A|B_2) = 0{,}2$. Tính $P(A)$. *Lời giải:* $P(A) = 0{,}4(0{,}1) + 0{,}6(0{,}2) = 0{,}04 + 0{,}12 = 0{,}16$.

* **Bài 19.5 \[Thông hiểu\]:** Với số liệu Bài 19.4, tính xác suất hậu nghiệm $P(B_1|A)$. *Lời giải:* $P(B_1|A) = \dfrac{P(B_1)P(A|B_1)}{P(A)} = \dfrac{0{,}04}{0{,}16} = 0{,}25 = 25\%$.

* **Bài 19.6 \[Thông hiểu\]:** Một kho hàng có 2 lô sản phẩm: Lô 1 có 8 chính phẩm, 2 phế phẩm; Lô 2 có 7 chính phẩm, 3 phế phẩm. Chọn ngẫu nhiên 1 lô rồi lấy 1 sản phẩm. Tính xác suất lấy được chính phẩm. *Lời giải:* $P(L_1) = P(L_2) = 0{,}5$. $P(C|L_1) = 8/10 = 0{,}8; P(C|L_2) = 7/10 = 0{,}7$. $P(C) = 0{,}5(0{,}8) + 0{,}5(0{,}7) = 0{,}75 = 75\%$.

* **Bài 19.7 \[Thông hiểu\]:** Nếu lấy được chính phẩm ở Bài 19.6, tính xác suất để chính phẩm đó thuộc Lô 1. *Lời giải:* $P(L_1|C) = \dfrac{P(L_1)P(C|L_1)}{P(C)} = \dfrac{0{,}5(0{,}8)}{0{,}75} = \dfrac{0{,}4}{0{,}75} = \dfrac{8}{15} \approx 53{,}33\%$.

* **Bài 19.8 \[Vận dụng - Bài toán xét nghiệm Y học kinh điển\]:** Một căn bệnh có tỉ lệ mắc trong cộng đồng là $1\%$ ($P(B) = 0{,}01$). Một que thử y tế có độ nhạy $98\%$ (người có bệnh thử ra dương tính với xác suất $0{,}98$) và độ đặc hiệu $95\%$ (người không bệnh thử ra âm tính với xác suất $0{,}95$, tức dương tính giả $5\%$). Một người ngẫu nhiên đi xét nghiệm cho kết quả dương tính. Tính xác suất thực sự người đó bị bệnh. *Lời giải:* $P(B) = 0{,}01 \Rightarrow P(\bar{B}) = 0{,}99$. $P(+|B) = 0{,}98; P(+|\bar{B}) = 0{,}05$. Theo công thức xác suất toàn phần: $P(+) = 0{,}01(0{,}98) + 0{,}99(0{,}05) = 0{,}0098 + 0{,}0495 = 0{,}0593$. Theo công thức Bayes: 

  $$
  P(B|+) = \dfrac{0{,}0098}{0{,}0593} \approx 0{,}1653 = 16{,}53\%
  $$

   *Nhận xét sư phạm quan trọng:* Dù que thử có độ chính xác trên $95\%$, một người có kết quả dương tính chỉ có khoảng $16{,}5\%$ cơ hội thực sự mắc bệnh do tỉ lệ mắc bệnh trong cộng đồng quá hiếm ($1\%$). Cần phải xét nghiệm khẳng định lần 2!

* **Bài 19.9 \[Vận dụng\]:** Một ngân hàng phân loại khách hàng vay vốn: Nhóm tốt chiếm $80\%$, Nhóm rủi ro chiếm $20\%$. Tỉ lệ trễ hạn trả nợ của Nhóm tốt là $1\%$, của Nhóm rủi ro là $15\%$. Một khách hàng được ghi nhận trễ hạn nợ, tính xác suất khách hàng này thuộc Nhóm rủi ro. *Lời giải:* $P(T) = 0{,}8, P(R) = 0{,}2$. $P(\text{Trễ}|T) = 0{,}01, P(\text{Trễ}|R) = 0{,}15$. $P(\text{Trễ}) = 0{,}8(0{,}01) + 0{,}2(0{,}15) = 0{,}008 + 0{,}030 = 0{,}038$. $P(R|\text{Trễ}) = \dfrac{0{,}030}{0{,}038} = \dfrac{30}{38} = \dfrac{15}{19} \approx 78{,}95\%$.

* **Bài 19.10 \[Vận dụng\]:** Một hệ thống lọc email rác (spam) phân loại: Email bình thường chiếm $90\%$, email rác chiếm $10\%$. Từ khóa "Khuyến mãi lớn" xuất hiện trong $80\%$ email rác và chỉ xuất hiện trong $2\%$ email bình thường. Một email gửi đến có chứa từ khóa "Khuyến mãi lớn". Tính xác suất để email này đúng là email rác. *Lời giải:* $P(S) = 0{,}1, P(N) = 0{,}9$. $P(K|S) = 0{,}8, P(K|N) = 0{,}02$. $P(K) = 0{,}1(0{,}8) + 0{,}9(0{,}02) = 0{,}08 + 0{,}018 = 0{,}098$. $P(S|K) = \dfrac{0{,}08}{0{,}098} = \dfrac{80}{98} = \dfrac{40}{49} \approx 81{,}63\%$.

## HỆ THỐNG CÁC ĐỀ KIỂM TRA CHUẨN CÔNG VĂN 7991 (2 DẠNG ĐỀ) CHO CHƯƠNG III, IV, V, VI

Tất cả các đề kiểm tra của từng chương đều được biên soạn đúng ma trận và quy cách:

* **Dạng 1 (Đề có Tự luận — 4 phần 21 câu = 10,0đ):** 12 MCQ (3đ) + 2 Đ/S (2đ) + 4 TLN (2đ) + 3 Tự luận (3đ).

* **Dạng 2 (Đề Trắc nghiệm khách quan — 3 phần 22 câu = 10,0đ):** 12 MCQ (3đ) + 4 Đ/S (4đ) + 6 TLN (3đ).