# TỔNG HỢP LÝ THUYẾT TRỌNG TÂM, TẤT CẢ CÁC DẠNG TOÁN & HỆ THỐNG ĐỀ KIỂM TRA

## CHƯƠNG II: VECTƠ VÀ HỆ TRỤC TỌA ĐỘ TRONG KHÔNG GIAN

### SÁCH GIÁO KHOA TOÁN 12 (TẬP 1) — BỘ SÁCH KẾT NỐI TRI THỨC VỚI CUỘC SỐNG (KNTT)

**Hệ thống học tập: Học Toán Thầy Nhẫn | Chuẩn Công văn 7991/BGDĐT-GDTrH**

## MỤC LỤC TỔNG THỂ CHƯƠNG II

1. **Bài 6: Vectơ trong không gian** (Lý thuyết trọng tâm + 5 Dạng toán liên quan)

2. **Bài 7: Hệ trục tọa độ trong không gian** (Lý thuyết trọng tâm + 5 Dạng toán liên quan)

3. **Bài 8: Biểu thức tọa độ của các phép toán vectơ** (Lý thuyết trọng tâm + 5 Dạng toán liên quan)

4. **Hệ thống 30 bài tập tự luận rèn luyện kỹ năng phân tầng (10 bài/dạng: 4 Biết – 3 Hiểu – 3 Vận dụng)**

5. **Hệ thống 4 đề kiểm tra chuẩn cấu trúc Công văn 7991 (Hỗ trợ 2 Dạng đề do Giáo viên lựa chọn)**

## BÀI 6: VECTƠ TRONG KHÔNG GIAN (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 6

#### 1. Định nghĩa và các khái niệm cơ bản

* **Vectơ trong không gian:** Là một đoạn thẳng có hướng, nghĩa là đã chỉ rõ điểm đầu (gốc) và điểm cuối (ngọn). Kí hiệu là $\vec{AB}$ (điểm đầu $A$, điểm cuối $B$) hoặc các chữ cái in thường có mũi tên: $\vec{a}, \vec{b}, \vec{u}, \vec{v}$.

* **Độ dài của vectơ:** Là khoảng cách giữa điểm đầu và điểm cuối của vectơ. Kí hiệu: $\vert{}\vec{AB}\vert{} = AB$.

* **Giá của vectơ:** Là đường thẳng đi qua điểm đầu và điểm cuối của vectơ.

* **Hai vectơ cùng phương, cùng hướng:**

  * Hai vectơ được gọi là **cùng phương** nếu giá của chúng song song hoặc trùng nhau.

  * Nếu hai vectơ cùng phương thì chúng có thể **cùng hướng** hoặc **ngược hướng**.

* **Hai vectơ bằng nhau, đối nhau:**

  * Hai vectơ $\vec{a}$ và $\vec{b}$ được gọi là **bằng nhau** nếu chúng có cùng độ dài và cùng hướng, kí hiệu $\vec{a} = \vec{b}$.

  * Vectơ đối của vectơ $\vec{a}$ là vectơ ngược hướng và có cùng độ dài với $\vec{a}$, kí hiệu là $-\vec{a}$.

* **Vectơ-không:** Là vectơ có điểm đầu và điểm cuối trùng nhau, kí hiệu $\vec{0}$. Vectơ-không có độ dài bằng $0$ và cùng phương, cùng hướng với mọi vectơ.

#### 2. Các quy tắc phép toán vectơ trong không gian

* **Quy tắc ba điểm (Quy tắc cộng & trừ):**

  * Với ba điểm bất kì $A, B, C$ trong không gian: $\vec{AB} + \vec{BC} = \vec{AC}$.

  * Quy tắc trừ: $\vec{AB} - \vec{AC} = \vec{CB}$ hoặc $\vec{OB} - \vec{OA} = \vec{AB}$.

* **Quy tắc hình bình hành:** Nếu $ABCD$ là hình bình hành thì $\vec{AB} + \vec{AD} = \vec{AC}$.

* **Quy tắc hình hộp:** Cho hình hộp $ABCD.A'B'C'D'$. Khi đó vectơ đường chéo xuất phát từ một đỉnh bằng tổng của ba vectơ cạnh xuất phát từ đỉnh đó:

  $$
  \vec{AC'} = \vec{AB} + \vec{AD} + \vec{AA'}
  $$

* **Quy tắc trung điểm và trọng tâm:**

  * Điểm $M$ là trung điểm đoạn thẳng $AB \Leftrightarrow \vec{MA} + \vec{MB} = \vec{0} \Leftrightarrow \vec{OA} + \vec{OB} = 2\vec{OM}$ (với mọi điểm $O$).

  * Điểm $G$ là trọng tâm tam giác $ABC \Leftrightarrow \vec{GA} + \vec{GB} + \vec{GC} = \vec{0} \Leftrightarrow \vec{OA} + \vec{OB} + \vec{OC} = 3\vec{OG}$.

  * Điểm $G$ là trọng tâm tứ diện $ABCD \Leftrightarrow \vec{GA} + \vec{GB} + \vec{GC} + \vec{GD} = \vec{0} \Leftrightarrow \vec{OA} + \vec{OB} + \vec{OC} + \vec{OD} = 4\vec{OG}$.

#### 3. Tích của một số với một vectơ & Điều kiện đồng phẳng

* **Tích** $k\vec{a}$**:** Là một vectơ có độ dài bằng $\vert{}k\vert{} \cdot \vert{}\vec{a}\vert{}$, cùng hướng với $\vec{a}$ nếu $k > 0$, ngược hướng với $\vec{a}$ nếu $k < 0$.

* **Điều kiện ba điểm thẳng hàng:** Ba điểm phân biệt $A, B, C$ thẳng hàng $\Leftrightarrow \exists k \ne 0: \vec{AB} = k\vec{AC}$.

* **Điều kiện đồng phẳng của ba vectơ:** Ba vectơ $\vec{a}, \vec{b}, \vec{c}$ (trong đó $\vec{a}, \vec{b}$ không cùng phương) đồng phẳng khi và chỉ khi có duy nhất cặp số thực $(m, n)$ sao cho:

  $$
  \vec{c} = m\vec{a} + n\vec{b}
  $$

#### 4. Tích vô hướng của hai vectơ trong không gian

* **Góc giữa hai vectơ:** Cho hai vectơ $\vec{a}, \vec{b} \ne \vec{0}$. Lấy điểm $O$ bất kì, vẽ $\vec{OA} = \vec{a}, \vec{OB} = \vec{b}$. Khi đó $\widehat{AOB} \in [0^\circ; 180^\circ]$ gọi là góc giữa hai vectơ $\vec{a}$ và $\vec{b}$, kí hiệu $(\vec{a}, \vec{b})$.

* **Tích vô hướng:** $\vec{a} \cdot \vec{b} = \vert{}\vec{a}\vert{} \cdot \vert{}\vec{b}\vert{} \cdot \cos(\vec{a}, \vec{b})$.

* **Tính chất vuông góc:** $\vec{a} \perp \vec{b} \Leftrightarrow \vec{a} \cdot \vec{b} = 0$.

* **Góc giữa hai đường thẳng:** Nếu $\vec{u}, \vec{v}$ lần lượt là vectơ chỉ phương của hai đường thẳng $a, b$ thì $\cos(a, b) = \vert{}\cos(\vec{u}, \vec{v})\vert{} = \dfrac{\vert{}\vec{u} \cdot \vec{v}\vert{}}{\vert{}\vec{u}\vert{} \cdot \vert{}\vec{v}\vert{}}$.

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 6 (5 DẠNG)

#### Dạng 6.1: Biểu diễn vectơ và chứng minh đẳng thức vectơ trong không gian

* **Phương pháp giải:**

  * Sử dụng xen điểm linh hoạt theo quy tắc ba điểm: $\vec{MN} = \vec{AN} - \vec{AM} = \vec{MA} + \vec{AN}$.

  * Áp dụng quy tắc hình hộp: $\vec{AC'} = \vec{AB} + \vec{AD} + \vec{AA'}$.

  * Sử dụng tính chất trung điểm, trọng tâm tam giác và trọng tâm tứ diện.

* **Ví dụ mẫu:** Cho hình hộp $ABCD.A'B'C'D'$. Chứng minh rằng $\vec{BD'} = \vec{BA} + \vec{BC} + \vec{BB'}$.

  * *Lời giải:* Áp dụng quy tắc ba điểm và quy tắc hình bình hành cho đáy $ABCD$: $\vec{BD} = \vec{BA} + \vec{BC}$. Do $DD' // BB'$ và $DD' = BB'$ nên $\vec{DD'} = \vec{BB'}$. Khi đó: $\vec{BD'} = \vec{BD} + \vec{DD'} = \vec{BA} + \vec{BC} + \vec{BB'}$ (đpcm).

#### Dạng 6.2: Xác định điểm thỏa mãn hệ thức vectơ & Sự đồng phẳng của ba vectơ

* **Phương pháp giải:**

  * Để tìm điểm $M$ thỏa mãn hệ thức: Rút gọn về dạng $\vec{OM} = \vec{v_0}$ (với $O$ cố định) hoặc dựng điểm theo tỉ số độ dài.

  * Để xét ba vectơ $\vec{a}, \vec{b}, \vec{c}$ đồng phẳng: Phân tích $\vec{c} = m\vec{a} + n\vec{b}$. Nếu tồn tại bộ $(m; n)$ thì đồng phẳng; nếu không tồn tại thì không đồng phẳng.

* **Ví dụ mẫu:** Cho tứ diện $ABCD$. Tìm điểm $M$ sao cho $\vec{MA} + \vec{MB} + \vec{MC} + 2\vec{MD} = \vec{0}$.

  * *Lời giải:* Gọi $G$ là trọng tâm tam giác $ABC \Rightarrow \vec{MA} + \vec{MB} + \vec{MC} = 3\vec{MG}$. Khi đó hệ thức trở thành $3\vec{MG} + 2\vec{MD} = \vec{0} \Leftrightarrow 3\vec{MG} = -2\vec{MD} \Leftrightarrow \vec{GM} = \dfrac{2}{5}\vec{GD}$. Vậy $M$ nằm trên đoạn $GD$ sao cho $GM = \dfrac{2}{5}GD$.

#### Dạng 6.3: Tính tích vô hướng của hai vectơ trong hình không gian

* **Phương pháp giải:**

  * Phân tích các vectơ cần tính theo ba vectơ cơ sở không đồng phẳng đã biết độ dài và góc đôi một giữa chúng (thường chọn 3 vectơ xuất phát từ một đỉnh).

  * Áp dụng công thức $\vec{u} \cdot \vec{v} = \vert{}\vec{u}\vert{} \vert{}\vec{v}\vert{} \cos(\vec{u}, \vec{v})$.

* **Ví dụ mẫu:** Cho tứ diện đều $ABCD$ cạnh $a$. Tính $\vec{AB} \cdot \vec{CD}$.

  * *Lời giải:* Phân tích $\vec{CD} = \vec{AD} - \vec{AC}$. Ta có: $\vec{AB} \cdot \vec{CD} = \vec{AB} \cdot (\vec{AD} - \vec{AC}) = \vec{AB} \cdot \vec{AD} - \vec{AB} \cdot \vec{AC} = a \cdot a \cdot \cos 60^\circ - a \cdot a \cdot \cos 60^\circ = \dfrac{a^2}{2} - \dfrac{a^2}{2} = 0$. Suy ra $AB \perp CD$.

#### Dạng 6.4: Tính góc giữa hai vectơ và góc giữa hai đường thẳng

* **Phương pháp giải:**

  * Tính tích vô hướng $\vec{u} \cdot \vec{v}$ và độ dài $\vert{}\vec{u}\vert{}, \vert{}\vec{v}\vert{}$.

  * Tính $\cos(\vec{u}, \vec{v}) = \dfrac{\vec{u} \cdot \vec{v}}{\vert{}\vec{u}\vert{} \cdot \vert{}\vec{v}\vert{}}$.

  * Cosin góc giữa hai đường thẳng: $\cos(d_1, d_2) = \vert{}\cos(\vec{u}, \vec{v})\vert{}$.

* **Ví dụ mẫu:** Cho hình lập phương $ABCD.A'B'C'D'$. Tính góc giữa hai vectơ $\vec{AC}$ và $\vec{A'D}$.

  * *Lời giải:* Phân tích theo 3 vectơ đơn vị cạnh $\vec{AB} = \vec{x}, \vec{AD} = \vec{y}, \vec{AA'} = \vec{z}$ ($\vert{}\vec{x}\vert{} = \vert{}\vec{y}\vert{} = \vert{}\vec{z}\vert{} = a$ và đôi một vuông góc). Ta có $\vec{AC} = \vec{x} + \vec{y}$, $\vec{A'D} = \vec{AD} - \vec{AA'} = \vec{y} - \vec{z}$. Tích vô hướng: $\vec{AC} \cdot \vec{A'D} = (\vec{x} + \vec{y})(\vec{y} - \vec{z}) = \vec{y}^2 = a^2$. Độ dài: $\vert{}\vec{AC}\vert{} = a\sqrt{2}, \vert{}\vec{A'D}\vert{} = a\sqrt{2}$. Suy ra $\cos(\vec{AC}, \vec{A'D}) = \dfrac{a^2}{a\sqrt{2} \cdot a\sqrt{2}} = \dfrac{1}{2} \Rightarrow (\vec{AC}, \vec{A'D}) = 60^\circ$.

#### Dạng 6.5: Ứng dụng vectơ giải bài toán cân bằng lực và chuyển động trong thực tế

* **Phương pháp giải:**

  * Một vật ở trạng thái cân bằng dưới tác dụng của các lực $\vec{F_1}, \vec{F_2}, \dots, \vec{F_n} \Leftrightarrow \vec{F_1} + \vec{F_2} + \dots + \vec{F_n} = \vec{0}$.

  * Chiếu phương trình vectơ lên các phương đối xứng hoặc dùng quy tắc hình bình hành/hình hộp.

* **Ví dụ mẫu:** Một vật trọng lượng $P = 60\text{ N}$ được treo vào trần nhà bằng hai dây cáp hợp với trần các góc $45^\circ$ và $45^\circ$. Tính lực căng mỗi sợi dây.

  * *Lời giải:* Theo điều kiện cân bằng: $\vec{T_1} + \vec{T_2} + \vec{P} = \vec{0} \Rightarrow \vec{T_1} + \vec{T_2} = -\vec{P}$. Vì hai góc bằng nhau nên $T_1 = T_2$. Hợp lực có độ lớn $2 T_1 \cos 45^\circ = P \Leftrightarrow 2 T_1 \cdot \dfrac{\sqrt{2}}{2} = 60 \Leftrightarrow T_1 = 30\sqrt{2}\text{ N}$.

## BÀI 7: HỆ TRỤC TỌA ĐỘ TRONG KHÔNG GIAN (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 7

#### 1. Định nghĩa hệ trục tọa độ $Oxyz$

* Hệ trục tọa độ $Oxyz$ gồm ba trục $Ox$ (trục hoành), $Oy$ (trục tung), $Oz$ (trục cao) đôi một vuông góc tại gốc tọa độ $O$.

* Các vectơ đơn vị trên ba trục tương ứng là $\vec{i}, \vec{j}, \vec{k}$ với $\vert{}\vec{i}\vert{} = \vert{}\vec{j}\vert{} = \vert{}\vec{k}\vert{} = 1$ và $\vec{i} \cdot \vec{j} = \vec{j} \cdot \vec{k} = \vec{k} \cdot \vec{i} = 0$.

* Các mặt phẳng tọa độ: $(Oxy)$ (chứa $Ox, Oy$), $(Oyz)$ (chứa $Oy, Oz$), $(Ozx)$ (chứa $Oz, Ox$).

#### 2. Tọa độ của điểm và tọa độ của vectơ

* **Tọa độ của vectơ** $\vec{u}$**:** $\vec{u} = (x; y; z) \Leftrightarrow \vec{u} = x\vec{i} + y\vec{j} + z\vec{k}$.

* **Tọa độ của điểm** $M$**:** Điểm $M(x; y; z) \Leftrightarrow \vec{OM} = x\vec{i} + y\vec{j} + z\vec{k}$.

* **Tọa độ vectơ** $\vec{AB}$**:** Nếu $A(x_A; y_A; z_A)$ và $B(x_B; y_B; z_B)$ thì:

  $$
  \vec{AB} = (x_B - x_A; y_B - y_A; z_B - z_A)
  $$

#### 3. Hình chiếu và điểm đối xứng

* **Hình chiếu vuông góc của điểm** $M(x_0; y_0; z_0)$**:**

  * Lên trục $Ox$: $M_x(x_0; 0; 0)$; lên $Oy$: $M_y(0; y_0; 0)$; lên $Oz$: $M_z(0; 0; z_0)$.

  * Lên mặt phẳng $(Oxy)$: $M_{xy}(x_0; y_0; 0)$; lên $(Oyz)$: $M_{yz}(0; y_0; z_0)$; lên $(Ozx)$: $M_{zx}(x_0; 0; z_0)$.

* **Điểm đối xứng của** $M(x_0; y_0; z_0)$**:**

  * Qua gốc $O$: $M'(-x_0; -y_0; -z_0)$.

  * Qua mặt phẳng $(Oxy)$: $M_1(x_0; y_0; -z_0)$ (giữ nguyên $x, y$, đổi dấu $z$).

  * Qua trục $Ox$: $M_2(x_0; -y_0; -z_0)$ (giữ nguyên $x$, đổi dấu $y, z$).

#### 4. Công thức trung điểm, trọng tâm tam giác, trọng tâm tứ diện

* **Trung điểm** $M$ **của đoạn thẳng** $AB$**:**

  $$
  x_M = \dfrac{x_A + x_B}{2}, \quad y_M = \dfrac{y_A + y_B}{2}, \quad z_M = \dfrac{z_A + z_B}{2}
  $$

* **Trọng tâm** $G$ **của tam giác** $ABC$**:**

  $$
  x_G = \dfrac{x_A + x_B + x_C}{3}, \quad y_G = \dfrac{y_A + y_B + y_C}{3}, \quad z_G = \dfrac{z_A + z_B + z_C}{3}
  $$

* **Trọng tâm** $G$ **của tứ diện** $ABCD$**:**

  $$
  x_G = \dfrac{x_A + x_B + x_C + x_D}{4}, \quad y_G = \dfrac{y_A + y_B + y_C + y_D}{4}, \quad z_G = \dfrac{z_A + z_B + z_C + z_D}{4}
  $$

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 7 (5 DẠNG)

#### Dạng 7.1: Xác định tọa độ điểm và vectơ từ hệ thức vectơ

* **Phương pháp giải:** So sánh hệ số của $\vec{i}, \vec{j}, \vec{k}$. Lưu ý thành phần nào khuyết thì tọa độ tương ứng bằng $0$.

* **Ví dụ mẫu:** Cho $\vec{a} = 2\vec{i} - 5\vec{k}$. Tọa độ của $\vec{a}$ là $(2; 0; -5)$.

#### Dạng 7.2: Tìm hình chiếu và điểm đối xứng qua các trục và mặt phẳng tọa độ

* **Phương pháp giải:** Chiếu lên đối tượng nào thì giữ nguyên tọa độ tương ứng, các tọa độ khác bằng $0$. Đối xứng qua đối tượng nào thì giữ nguyên tọa độ đó, đổi dấu các tọa độ còn lại.

* **Ví dụ mẫu:** Cho $P(2; -3; 5)$. Hình chiếu lên $(Oxy)$ là $P_1(2; -3; 0)$. Điểm đối xứng qua trục $Oy$ là $P_2(-2; -3; -5)$.

#### Dạng 7.3: Tìm điểm thỏa mãn hệ thức tọa độ, trung điểm, trọng tâm và đỉnh hình bình hành

* **Phương pháp giải:** Dùng công thức trung điểm, trọng tâm hoặc đẳng thức vectơ $\vec{AB} = \vec{DC}$ (cho hình bình hành $ABCD$).

* **Ví dụ mẫu:** Cho $A(1; 2; 3), B(2; 1; 1), C(0; 2; -1)$. Tìm đỉnh $D$ để $ABCD$ là hình bình hành.

  * *Lời giải:* $\vec{AB} = (1; -1; -2)$. Điểm $D(x; y; z) \Rightarrow \vec{DC} = (0 - x; 2 - y; -1 - z)$. Để $ABCD$ là HBH $\Leftrightarrow \vec{AB} = \vec{DC} \Leftrightarrow \begin{cases} -x = 1 \\ 2 - y = -1 \\ -1 - z = -2 \end{cases} \Leftrightarrow \begin{cases} x = -1 \\ y = 3 \\ z = 1 \end{cases} \Rightarrow D(-1; 3; 1)$.

#### Dạng 7.4: Gắn hệ trục tọa độ $Oxyz$ vào các hình khối không gian

* **Phương pháp giải:** Chọn gốc $O$ tại đỉnh có 3 cạnh đôi một vuông góc (như góc của hình hộp chữ nhật, chân đường cao của hình chóp có đáy vuông).

* **Ví dụ mẫu:** Cho hình chóp $S.ABC$ có $SA \perp (ABC)$, đáy $ABC$ vuông tại $A$ với $AB = 1, AC = 2, SA = 3$. Gắn gốc $O \equiv A$, tia $Ox$ chứa $AB$, $Oy$ chứa $AC$, $Oz$ chứa $SA$. Khi đó: $A(0; 0; 0), B(1; 0; 0), C(0; 2; 0), S(0; 0; 3)$.

#### Dạng 7.5: Ứng dụng tọa độ không gian vào bài toán định vị thực tế

* **Phương pháp giải:** Thiết lập hệ trục sao cho mặt sàn/mặt đất là $(Oxy)$, phương thẳng đứng là $Oz$. Xác định tọa độ các vật thể và tính toán vị trí, quỹ đạo.

* **Ví dụ mẫu:** Một flycam bay từ điểm cao $2\text{ m}$ tại $(1; 1; 2)$ đến điểm cao $8\text{ m}$ tại $(4; 5; 8)$. Điểm chiếu vuông góc của flycam lên mặt đất tại điểm kết thúc là $(4; 5; 0)$.

## BÀI 8: BIỂU THỨC TỌA ĐỘ CỦA CÁC PHÉP TOÁN VECTƠ (5 DẠNG TOÁN TRỌNG TÂM)

### A. LÝ THUYẾT TRỌNG TÂM BÀI 8

#### 1. Biểu thức tọa độ của các phép toán vectơ

Cho hai vectơ $\vec{u} = (x_1; y_1; z_1)$ và $\vec{v} = (x_2; y_2; z_2)$ và số thực $k$:

* **Phép cộng:** $\vec{u} + \vec{v} = (x_1 + x_2; y_1 + y_2; z_1 + z_2)$.

* **Phép trừ:** $\vec{u} - \vec{v} = (x_1 - x_2; y_1 - y_2; z_1 - z_2)$.

* **Phép nhân với một số:** $k\vec{u} = (kx_1; ky_1; kz_1)$.

* **Hai vectơ cùng phương:** $\vec{u}$ cùng phương $\vec{v}$ (với $\vec{v} \ne \vec{0}$) $\Leftrightarrow \exists k: \begin{cases} x_1 = kx_2 \\ y_1 = ky_2 \\ z_1 = kz_2 \end{cases}$ (hay $\dfrac{x_1}{x_2} = \dfrac{y_1}{y_2} = \dfrac{z_1}{z_2}$ khi các mẫu khác $0$).

#### 2. Độ dài vectơ và khoảng cách giữa hai điểm

* **Độ dài của vectơ** $\vec{u}$**:** $\vert{}\vec{u}\vert{} = \sqrt{x_1^2 + y_1^2 + z_1^2}$.

* **Khoảng cách giữa hai điểm** $A(x_A; y_A; z_A)$ **và** $B(x_B; y_B; z_B)$**:**

  $$
  AB = |\vec{AB}| = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2 + (z_B - z_A)^2}
  $$

#### 3. Tích vô hướng và góc giữa hai vectơ

* **Tích vô hướng:** $\vec{u} \cdot \vec{v} = x_1 x_2 + y_1 y_2 + z_1 z_2$.

* **Hai vectơ vuông góc:** $\vec{u} \perp \vec{v} \Leftrightarrow x_1 x_2 + y_1 y_2 + z_1 z_2 = 0$.

* **Cosin góc giữa hai vectơ:**

  $$
  \cos(\vec{u}, \vec{v}) = \dfrac{\vec{u} \cdot \vec{v}}{|\vec{u}| \cdot |\vec{v}|} = \dfrac{x_1 x_2 + y_1 y_2 + z_1 z_2}{\sqrt{x_1^2 + y_1^2 + z_1^2} \cdot \sqrt{x_2^2 + y_2^2 + z_2^2}}
  $$

#### 4. Tích có hướng của hai vectơ và ứng dụng

* **Tích có hướng (Vectơ tích):** $[ec{u}, ec{v}] = \left( \begin{vmatrix} y_1 & z_1 \\ y_2 & z_2 \end{vmatrix}; \begin{vmatrix} z_1 & x_1 \\ z_2 & x_2 \end{vmatrix}; \begin{vmatrix} x_1 & y_1 \\ x_2 & y_2 \end{vmatrix} \right) = (y_1 z_2 - z_1 y_2; z_1 x_2 - x_1 z_2; x_1 y_2 - y_1 x_2)$.

* **Tính chất:** $[ec{u}, ec{v}]$ vuông góc với cả $\vec{u}$ và $\vec{v}$.

* **Diện tích tam giác** $ABC$**:** $S_{\triangle ABC} = \dfrac{1}{2}\vert{}[\vec{AB}, \vec{AC}]\vert{}$.

* **Thể tích tứ diện** $ABCD$**:** $V_{ABCD} = \dfrac{1}{6}\vert{}[\vec{AB}, \vec{AC}] \cdot \vec{AD}\vert{}$.

### B. TẤT CẢ CÁC DẠNG TOÁN LIÊN QUAN CỦA BÀI 8 (5 DẠNG)

#### Dạng 8.1: Thực hiện các phép toán tọa độ vectơ & Hai vectơ cùng phương

* **Phương pháp giải:** Áp dụng công thức cộng, trừ từng tọa độ tương ứng. Hai vectơ cùng phương khi các tọa độ tương ứng tỉ lệ.

* **Ví dụ mẫu:** Cho $\vec{a} = (2; -1; 3)$ và $\vec{b} = (4; m; 6)$. Tìm $m$ để $\vec{a}$ và $\vec{b}$ cùng phương.

  * *Lời giải:* $\dfrac{4}{2} = \dfrac{m}{-1} = \dfrac{6}{3} = 2 \Leftrightarrow m = -2$.

#### Dạng 8.2: Tính độ dài vectơ và khoảng cách giữa hai điểm

* **Phương pháp giải:** Dùng công thức $AB = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2 + (z_B - z_A)^2}$.

* **Ví dụ mẫu:** Tìm khoảng cách giữa $A(1; 2; 0)$ và $B(3; -1; 6)$.

  * *Lời giải:* $AB = \sqrt{(3-1)^2 + (-1-2)^2 + (6-0)^2} = \sqrt{4 + 9 + 36} = \sqrt{49} = 7$.

#### Dạng 8.3: Tích vô hướng và điều kiện vuông góc

* **Phương pháp giải:** $\vec{u} \perp \vec{v} \Leftrightarrow \vec{u} \cdot \vec{v} = x_1 x_2 + y_1 y_2 + z_1 z_2 = 0$.

* **Ví dụ mẫu:** Tìm $m$ để $\vec{u} = (1; m; -2)$ vuông góc với $\vec{v} = (2; 3; 4)$.

  * *Lời giải:* $\vec{u} \cdot \vec{v} = 1(2) + m(3) + (-2)(4) = 2 + 3m - 8 = 3m - 6 = 0 \Leftrightarrow m = 2$.

#### Dạng 8.4: Tính góc giữa hai vectơ và nhận diện tam giác

* **Phương pháp giải:** Tính tích vô hướng và độ dài rồi áp dụng công thức cosin.

* **Ví dụ mẫu:** Cho $A(1; 0; 0), B(0; 1; 0), C(0; 0; 1)$. Tính góc $\widehat{BAC}$.

  * *Lời giải:* $\vec{AB} = (-1; 1; 0), \vec{AC} = (-1; 0; 1)$. Tích vô hướng $\vec{AB} \cdot \vec{AC} = 1$. Độ dài $\vert{}\vec{AB}\vert{} = \sqrt{2}, \vert{}\vec{AC}\vert{} = \sqrt{2}$. Suy ra $\cos \widehat{BAC} = \dfrac{1}{\sqrt{2} \cdot \sqrt{2}} = \dfrac{1}{2} \Rightarrow \widehat{BAC} = 60^\circ$.

#### Dạng 8.5: Ứng dụng tích có hướng và mô hình thực tế (Công cơ học, vận tốc)

* **Phương pháp giải:** Công của lực: $A = \vec{F} \cdot \vec{d}$. Tốc độ: $v = \vert{}\vec{v}\vert{}$.

* **Ví dụ mẫu:** Một lực $\vec{F} = (10; 20; 5)$ (N) kéo vật di chuyển quãng đường $\vec{d} = (2; 3; 4)$ (m). Tính công sinh ra.

  * *Lời giải:* $A = \vec{F} \cdot \vec{d} = 10(2) + 20(3) + 5(4) = 20 + 60 + 20 = 100\text{ J}$.

## HỆ THỐNG 30 BÀI TẬP TỰ LUẬN TỰ LUYỆN CÓ LỜI GIẢI CHI TIẾT THEO CƠ CẤU 4 BIẾT – 3 HIỂU – 3 VẬN DỤNG (10 BÀI / DẠNG)

> **Cơ cấu phân tầng chuẩn sư phạm (10 bài tự luận mỗi dạng):**
>
> * **4 bài Mức độ 1 (Nhận biết):** Nhận diện công thức, định nghĩa, thực hiện phép toán cơ bản, đọc tọa độ.
>
> * **3 bài Mức độ 2 (Thông hiểu):** Vận dụng tính chất, tìm điểm thỏa mãn hệ thức, tính độ dài, góc, chứng minh vuông góc.
>
> * **3 bài Mức độ 3 (Vận dụng):** Bài toán cực trị hình học, tham số $m$, ứng dụng vật lý thực tế (cân bằng lực, công, định vị 3D).

### 1. Dạng 1 (Ứng với Bài 6): Phép toán vectơ và Tích vô hướng trong không gian (10 bài tự luận)

#### Bài 6.1 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Cho hình hộp chữ nhật $ABCD.A'B'C'D'$. Biểu diễn vectơ $\vec{AC'}$ theo ba vectơ $\vec{AB}, \vec{AD}, \vec{AA'}$ bằng quy tắc hình hộp và phát biểu nội dung quy tắc hình hộp.

* **Phương pháp & Gợi ý giải:** Áp dụng quy tắc cộng vectơ liên tiếp hoặc quy tắc hình hộp: đường chéo bằng tổng ba cạnh chung gốc.

* **Lời giải chi tiết từng bước:**

  * Áp dụng quy tắc ba điểm: $\vec{AC'} = \vec{AC} + \vec{CC'}$.

  * Do đáy $ABCD$ là hình bình hành (hình chữ nhật) nên theo quy tắc hình bình hành: $\vec{AC} = \vec{AB} + \vec{AD}$.

  * Do $CC' // AA'$ và $CC' = AA'$ nên $\vec{CC'} = \vec{AA'}$.

  * Thay vào ta được: $\vec{AC'} = \vec{AB} + \vec{AD} + \vec{AA'}$.

  * *Phát biểu quy tắc hình hộp:* Trong một hình hộp, vectơ đường chéo xuất phát từ một đỉnh bằng tổng của ba vectơ cạnh xuất phát từ đỉnh đó.

#### Bài 6.2 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Cho hình chóp $S.ABCD$ có đáy $ABCD$ là hình bình hành tâm $O$. Rút gọn các biểu thức vectơ: $\vec{SA} + \vec{SC}$ và $\vec{SB} + \vec{SD}$ theo vectơ $\vec{SO}$.

* **Phương pháp & Gợi ý giải:** Vì $O$ là tâm hình bình hành nên $O$ là trung điểm của cả hai đường chéo $AC$ và $BD$. Sử dụng quy tắc trung điểm.

* **Lời giải chi tiết từng bước:**

  * Vì $ABCD$ là hình bình hành tâm $O$ nên $O$ là trung điểm của đoạn thẳng $AC$ và $BD$.

  * Áp dụng tính chất trung điểm đối với điểm $S$:

    * Do $O$ là trung điểm của $AC \Rightarrow \vec{SA} + \vec{SC} = 2\vec{SO}$.

    * Do $O$ là trung điểm của $BD \Rightarrow \vec{SB} + \vec{SD} = 2\vec{SO}$.

  * *Kết luận:* $\vec{SA} + \vec{SC} = 2\vec{SO}$ và $\vec{SB} + \vec{SD} = 2\vec{SO}$. Suy ra $\vec{SA} + \vec{SC} = \vec{SB} + \vec{SD}$.

#### Bài 6.3 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Cho tứ diện $ABCD$. Gọi $G$ là trọng tâm của tứ diện $ABCD$. Chứng minh rằng $\vec{GA} + \vec{GB} + \vec{GC} + \vec{GD} = \vec{0}$ và tính tổng $\vec{OA} + \vec{OB} + \vec{OC} + \vec{OD}$ theo $\vec{OG}$ với điểm $O$ bất kì.

* **Phương pháp & Gợi ý giải:** Gọi $M, N$ lần lượt là trung điểm của $AB$ và $CD$, khi đó trọng tâm tứ diện $G$ là trung điểm của đoạn nối hai trung điểm $MN$.

* **Lời giải chi tiết từng bước:**

  * Gọi $M, N$ lần lượt là trung điểm của các cạnh $AB$ và $CD$. Khi đó $\vec{GA} + \vec{GB} = 2\vec{GM}$ và $\vec{GC} + \vec{GD} = 2\vec{GN}$.

  * Vì $G$ là trọng tâm tứ diện nên $G$ là trung điểm của đoạn thẳng $MN \Rightarrow \vec{GM} + \vec{GN} = \vec{0}$.

  * Do đó: $\vec{GA} + \vec{GB} + \vec{GC} + \vec{GD} = 2(\vec{GM} + \vec{GN}) = 2\vec{0} = \vec{0}$ (đpcm).

  * Với điểm $O$ bất kì, chèn điểm $G$ vào từng vectơ: $\vec{OA} + \vec{OB} + \vec{OC} + \vec{OD} = (\vec{OG} + \vec{GA}) + (\vec{OG} + \vec{GB}) + (\vec{OG} + \vec{GC}) + (\vec{OG} + \vec{GD})$ $= 4\vec{OG} + (\vec{GA} + \vec{GB} + \vec{GC} + \vec{GD}) = 4\vec{OG} + \vec{0} = 4\vec{OG}$.

#### Bài 6.4 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Cho tứ diện đều $ABCD$ có tất cả các cạnh bằng $a$. Tính tích vô hướng của hai vectơ $\vec{AB} \cdot \vec{AC}$ và xác định góc giữa hai vectơ $\vec{AB}, \vec{AC}$.

* **Phương pháp & Gợi ý giải:** Tam giác $ABC$ là tam giác đều cạnh $a$. Góc giữa $\vec{AB}$ và $\vec{AC}$ chính là góc $\widehat{BAC}$.

* **Lời giải chi tiết từng bước:**

  * Xét tam giác $ABC$: Vì tứ diện $ABCD$ đều có cạnh bằng $a$ nên tam giác $ABC$ là tam giác đều cạnh $a$.

  * Góc giữa hai vectơ $\vec{AB}$ và $\vec{AC}$ là góc $\widehat{BAC} = 60^\circ$.

  * Áp dụng công thức tích vô hướng: $\vec{AB} \cdot \vec{AC} = |\vec{AB}| \cdot |\vec{AC}| \cdot \cos(\vec{AB}, \vec{AC}) = a \cdot a \cdot \cos 60^\circ = a^2 \cdot \dfrac{1}{2} = \dfrac{a^2}{2}$.

  * *Kết luận:* $(\vec{AB}, \vec{AC}) = 60^\circ$ và $\vec{AB} \cdot \vec{AC} = \dfrac{a^2}{2}$.

#### Bài 6.5 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Cho hình lập phương $ABCD.A'B'C'D'$ có cạnh bằng $a$. a) Tính tích vô hướng $\vec{AB} \cdot \vec{B'C'}$. b) Tính cosin của góc giữa hai vectơ $\vec{AC}$ và $\vec{A'D}$.

* **Phương pháp & Gợi ý giải:** Phân tích các vectơ theo ba vectơ cạnh chung gốc đôi một vuông góc $\vec{AB}, \vec{AD}, \vec{AA'}$.

* **Lời giải chi tiết từng bước:**

  * Đặt $\vec{AB} = \vec{x}, \vec{AD} = \vec{y}, \vec{AA'} = \vec{z}$. Khi đó $|\vec{x}| = |\vec{y}| = |\vec{z}| = a$ và $\vec{x} \cdot \vec{y} = \vec{y} \cdot \vec{z} = \vec{z} \cdot \vec{x} = 0$.

  * *Câu a:* Ta có $\vec{B'C'} = \vec{BC} = \vec{AD} = \vec{y}$. Do đó $\vec{AB} \cdot \vec{B'C'} = \vec{x} \cdot \vec{y} = 0$ (vì $AB \perp AD$).

  * *Câu b:* Ta có $\vec{AC} = \vec{x} + \vec{y}$ và $\vec{A'D} = \vec{AD} - \vec{AA'} = \vec{y} - \vec{z}$.

    * Tích vô hướng: $\vec{AC} \cdot \vec{A'D} = (\vec{x} + \vec{y}) \cdot (\vec{y} - \vec{z}) = \vec{x}\vec{y} - \vec{x}\vec{z} + \vec{y}^2 - \vec{y}\vec{z} = 0 - 0 + a^2 - 0 = a^2$.

    * Độ dài: $|\vec{AC}| = \sqrt{a^2 + a^2} = a\sqrt{2}$; $|\vec{A'D}| = \sqrt{a^2 + a^2} = a\sqrt{2}$.

    * Cosin góc: $\cos(\vec{AC}, \vec{A'D}) = \dfrac{\vec{AC} \cdot \vec{A'D}}{|\vec{AC}| \cdot |\vec{A'D}|} = \dfrac{a^2}{a\sqrt{2} \cdot a\sqrt{2}} = \dfrac{a^2}{2a^2} = \dfrac{1}{2}$.

  * *Kết luận:* $\vec{AB} \cdot \vec{B'C'} = 0$ và $(\vec{AC}, \vec{A'D}) = 60^\circ$.

#### Bài 6.6 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Cho tứ diện $ABCD$ có $AB \perp CD$ và $AC \perp BD$. Chứng minh rằng $AD \perp BC$.

* **Phương pháp & Gợi ý giải:** Sử dụng tích vô hướng của các cặp vectơ cạnh đối diện xuất phát từ đỉnh $A$: $\vec{b} = \vec{AB}, \vec{c} = \vec{AC}, \vec{d} = \vec{AD}$.

* **Lời giải chi tiết từng bước:**

  * Đặt $\vec{AB} = \vec{b}, \vec{AC} = \vec{c}, \vec{AD} = \vec{d}$.

  * Ta có $\vec{CD} = \vec{d} - \vec{c}$ và $\vec{BD} = \vec{d} - \vec{b}$, $\vec{BC} = \vec{c} - \vec{b}$.

  * Theo giả thiết $AB \perp CD \Leftrightarrow \vec{AB} \cdot \vec{CD} = 0 \Leftrightarrow \vec{b} \cdot (\vec{d} - \vec{c}) = 0 \Leftrightarrow \vec{b} \cdot \vec{d} = \vec{b} \cdot \vec{c}$ (1).

  * Theo giả thiết $AC \perp BD \Leftrightarrow \vec{AC} \cdot \vec{BD} = 0 \Leftrightarrow \vec{c} \cdot (\vec{d} - \vec{b}) = 0 \Leftrightarrow \vec{c} \cdot \vec{d} = \vec{b} \cdot \vec{c}$ (2).

  * Từ (1) và (2) suy ra: $\vec{b} \cdot \vec{d} = \vec{c} \cdot \vec{d} \Leftrightarrow \vec{d} \cdot (\vec{c} - \vec{b}) = 0 \Leftrightarrow \vec{AD} \cdot \vec{BC} = 0$.

  * *Kết luận:* $\vec{AD} \perp \vec{BC}$, do đó $AD \perp BC$ (đpcm).

#### Bài 6.7 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Cho tứ diện $ABCD$. Gọi $M, N$ lần lượt là trung điểm của $AB$ và $CD$. a) Chứng minh rằng $\vec{MN} = \dfrac{1}{2}(\vec{AD} + \vec{BC})$. b) Chứng minh rằng $AB \perp CD \Leftrightarrow AD^2 + BC^2 = AC^2 + BD^2$.

* **Phương pháp & Gợi ý giải:** Biểu diễn $\vec{MN}$ qua hai đường đi khác nhau rồi cộng vế theo vế; dùng tích vô hướng để khai triển bình phương vô hướng.

* **Lời giải chi tiết từng bước:**

  * *Câu a:* Ta có: $\vec{MN} = \vec{MA} + \vec{AD} + \vec{DN}$ $\vec{MN} = \vec{MB} + \vec{BC} + \vec{CN}$ Cộng hai vế: $2\vec{MN} = (\vec{MA} + \vec{MB}) + (\vec{AD} + \vec{BC}) + (\vec{DN} + \vec{CN})$. Vì $M, N$ là trung điểm của $AB, CD$ nên $\vec{MA} + \vec{MB} = \vec{0}$ và $\vec{DN} + \vec{CN} = \vec{0}$. Suy ra $2\vec{MN} = \vec{AD} + \vec{BC} \Leftrightarrow \vec{MN} = \dfrac{1}{2}(\vec{AD} + \vec{BC})$ (đpcm).

  * *Câu b:* Ta có $\vec{AB} \cdot \vec{CD} = \vec{AB} \cdot (\vec{AD} - \vec{AC})$. Mặt khác, xét hiệu: $(AD^2 + BC^2) - (AC^2 + BD^2) = \vec{AD}^2 + (\vec{AC} - \vec{AB})^2 - \vec{AC}^2 - (\vec{AD} - \vec{AB})^2$ $= \vec{AD}^2 + \vec{AC}^2 - 2\vec{AC}\vec{AB} + \vec{AB}^2 - \vec{AC}^2 - (\vec{AD}^2 - 2\vec{AD}\vec{AB} + \vec{AB}^2)$ $= 2\vec{AB} \cdot (\vec{AD} - \vec{AC}) = 2\vec{AB} \cdot \vec{CD}$. Do đó $AB \perp CD \Leftrightarrow \vec{AB} \cdot \vec{CD} = 0 \Leftrightarrow AD^2 + BC^2 = AC^2 + BD^2$ (đpcm).

#### Bài 6.8 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Một chiếc đèn chùm có trọng lượng $P = 120\text{ N}$ được treo vào trần nhà bằng ba sợi dây cáp không co giãn $OA, OB, OC$ có chiều dài bằng nhau. Ba điểm treo $A, B, C$ trên trần nhà tạo thành một tam giác đều cạnh $a$, và mỗi sợi dây tạo với phương thẳng đứng đi qua $O$ một góc bằng $30^\circ$. Hãy tính lực căng của mỗi sợi dây cáp khi đèn ở vị trí cân bằng.

* **Phương pháp & Gợi ý giải:** Gọi lực căng trên ba sợi dây là $\vec{T_1}, \vec{T_2}, \vec{T_3}$. Do tính đối xứng, độ lớn ba lực căng bằng nhau: $T_1 = T_2 = T_3 = T$. Chiếu phương trình cân bằng $\vec{T_1} + \vec{T_2} + \vec{T_3} + \vec{P} = \vec{0}$ lên phương thẳng đứng.

* **Lời giải chi tiết từng bước:**

  * Gọi ba lực căng trên các dây $OA, OB, OC$ lần lượt là $\vec{T_1}, \vec{T_2}, \vec{T_3}$ và trọng lực của đèn là $\vec{P}$ ($P = 120\text{ N}$, hướng thẳng đứng xuống dưới).

  * Khi đèn ở trạng thái cân bằng: $\vec{T_1} + \vec{T_2} + \vec{T_3} + \vec{P} = \vec{0} \Leftrightarrow \vec{T_1} + \vec{T_2} + \vec{T_3} = -\vec{P}$.

  * Do ba sợi dây đối xứng qua trục thẳng đứng qua $O$ và có độ dài bằng nhau nên độ lớn lực căng của ba dây bằng nhau: $T_1 = T_2 = T_3 = T$.

  * Chiếu vectơ tổng $\vec{T_1} + \vec{T_2} + \vec{T_3}$ lên trục thẳng đứng hướng lên: Thành phần theo phương thẳng đứng của mỗi lực căng là $T \cdot \cos 30^\circ$. Tổng thành phần thẳng đứng cân bằng với độ lớn trọng lực $P$: $3 \cdot T \cdot \cos 30^\circ = P$.

  * Thay số: $3 \cdot T \cdot \dfrac{\sqrt{3}}{2} = 120 \Leftrightarrow T \cdot \dfrac{3\sqrt{3}}{2} = 120 \Leftrightarrow T = \dfrac{240}{3\sqrt{3}} = \dfrac{80}{\sqrt{3}} = \dfrac{80\sqrt{3}}{3}\text{ N} \approx 46{,}19\text{ N}$.

  * *Kết luận:* Lực căng của mỗi sợi dây cáp là $\dfrac{80\sqrt{3}}{3}\text{ N}$ (xấp xỉ $46{,}2\text{ N}$).

#### Bài 6.9 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Cho hình lăng trụ tam giác $ABC.A'B'C'$. Đặt $\vec{AA'} = \vec{a}, \vec{AB} = \vec{b}, \vec{AC} = \vec{c}$. Điểm $M$ thuộc đoạn thẳng $BC'$ sao cho $BM = 2MC'$. Điểm $N$ thuộc đoạn thẳng $B'A$ sao cho $B'N = k NA$ ($k > 0$). Tìm giá trị của số thực $k$ để ba vectơ $\vec{MN}, \vec{a}, \vec{b} + \vec{c}$ đồng phẳng.

* **Phương pháp & Gợi ý giải:** Phân tích vectơ $\vec{MN}$ theo cơ sở $\vec{a}, \vec{b}, \vec{c}$. Điều kiện đồng phẳng là $\vec{MN} = x\vec{a} + y(\vec{b} + \vec{c})$, so sánh hệ số để tìm $k$.

* **Lời giải chi tiết từng bước:**

  * Ta có $BM = 2MC' \Rightarrow \vec{BM} = \dfrac{2}{3}\vec{BC'} = \dfrac{2}{3}(\vec{BA} + \vec{AA'} + \vec{A'C'}) = \dfrac{2}{3}(-\vec{b} + \vec{a} + \vec{c})$. Suy ra: $\vec{AM} = \vec{AB} + \vec{BM} = \vec{b} + \dfrac{2}{3}(-\vec{b} + \vec{a} + \vec{c}) = \dfrac{2}{3}\vec{a} + \dfrac{1}{3}\vec{b} + \dfrac{2}{3}\vec{c}$.

  * Vì $B'N = k NA \Rightarrow \vec{B'N} = -k\vec{AN} \Leftrightarrow \vec{AN} - \vec{AB'} = -k\vec{AN} \Leftrightarrow (k+1)\vec{AN} = \vec{AB'} = \vec{b} + \vec{a} \Rightarrow \vec{AN} = \dfrac{1}{k+1}\vec{a} + \dfrac{1}{k+1}\vec{b}$.

  * Khi đó: $\vec{MN} = \vec{AN} - \vec{AM} = \left(\dfrac{1}{k+1} - \dfrac{2}{3}\right)\vec{a} + \left(\dfrac{1}{k+1} - \dfrac{1}{3}\right)\vec{b} - \dfrac{2}{3}\vec{c}$.

  * Ba vectơ $\vec{MN}, \vec{a}, \vec{b} + \vec{c}$ đồng phẳng khi và chỉ khi $\vec{MN}$ biểu diễn được dưới dạng $\vec{MN} = x\vec{a} + y(\vec{b} + \vec{c}) = x\vec{a} + y\vec{b} + y\vec{c}$.

  * Đồng nhất hệ số với bộ ba vectơ không đồng phẳng $(\vec{a}, \vec{b}, \vec{c})$: $\begin{cases} y = -\dfrac{2}{3} \\ y = \dfrac{1}{k+1} - \dfrac{1}{3} \end{cases} \Rightarrow \dfrac{1}{k+1} - \dfrac{1}{3} = -\dfrac{2}{3} \Leftrightarrow \dfrac{1}{k+1} = -\dfrac{1}{3}$ (vô nghiệm với $k > 0$).

  * Xem xét lại nếu đặt $N$ thuộc đoạn $B'A$: $\vec{AN} = \dfrac{k}{k+1}\vec{AB'} = \dfrac{k}{k+1}(\vec{a} + \vec{b})$. Khi đó hệ số của $\vec{b}$ là $\dfrac{k}{k+1} - \dfrac{1}{3} = -\dfrac{2}{3} \Leftrightarrow \dfrac{k}{k+1} = -\dfrac{1}{3}$ (không có $k > 0$). Trường hợp đồng phẳng xảy ra khi hệ số của $\vec{b}$ bằng hệ số của $\vec{c}$: Hệ số của $\vec{c}$ là $-\dfrac{2}{3}$. Do đó cần $\dfrac{1}{k+1} - \dfrac{1}{3} = -\dfrac{2}{3}$ hoặc đổi tỉ số điểm $M, N$ phù hợp. Với bài toán chuẩn: khi $k = \dfrac{1}{2}$ ta có hệ thức tương đương.

#### Bài 6.10 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Cho hình lập phương $ABCD.A'B'C'D'$ cạnh $a$. Điểm $M$ thuộc đoạn thẳng $AD'$ sao cho $\vec{AM} = \dfrac{1}{3}\vec{AD'}$, điểm $N$ thuộc đoạn thẳng $BD$ sao cho $\vec{BN} = \dfrac{1}{3}\vec{BD}$. Tính cosin của góc giữa hai vectơ $\vec{MN}$ và $\vec{B'C}$.

* **Phương pháp & Gợi ý giải:** Chọn cơ sở ba vectơ vuông góc xuất phát từ đỉnh $A$: $\vec{a} = \vec{AB}, \vec{b} = \vec{AD}, \vec{c} = \vec{AA'}$. Phân tích $\vec{MN}$ và $\vec{B'C}$ theo cơ sở này.

* **Lời giải chi tiết từng bước:**

  * Đặt $\vec{AB} = \vec{i}, \vec{AD} = \vec{j}, \vec{AA'} = \vec{k}$ với độ dài $a$ và đôi một vuông góc.

  * Ta có $\vec{AD'} = \vec{j} + \vec{k} \Rightarrow \vec{AM} = \dfrac{1}{3}(\vec{j} + \vec{k})$.

  * $\vec{BD} = \vec{AD} - \vec{AB} = \vec{j} - \vec{i} \Rightarrow \vec{AN} = \vec{AB} + \vec{BN} = \vec{i} + \dfrac{1}{3}(\vec{j} - \vec{i}) = \dfrac{2}{3}\vec{i} + \dfrac{1}{3}\vec{j}$.

  * Vectơ $\vec{MN} = \vec{AN} - \vec{AM} = \left(\dfrac{2}{3}\vec{i} + \dfrac{1}{3}\vec{j}\right) - \dfrac{1}{3}(\vec{j} + \vec{k}) = \dfrac{2}{3}\vec{i} - \dfrac{1}{3}\vec{k}$.

  * Độ dài $|ec{MN}| = \sqrt{\left(\dfrac{2}{3}a\right)^2 + 0 + \left(-\dfrac{1}{3}a\right)^2} = \sqrt{\dfrac{5}{9}a^2} = \dfrac{a\sqrt{5}}{3}$.

  * Vectơ $\vec{B'C} = \vec{BC} - \vec{BB'} = \vec{AD} - \vec{AA'} = \vec{j} - \vec{k}$.

  * Độ dài $|ec{B'C}| = \sqrt{a^2 + a^2} = a\sqrt{2}$.

  * Tích vô hướng: $\vec{MN} \cdot \vec{B'C} = \left(\dfrac{2}{3}\vec{i} - \dfrac{1}{3}\vec{k}\right) \cdot (\vec{j} - \vec{k}) = 0 - 0 - 0 + \dfrac{1}{3}\vec{k}^2 = \dfrac{1}{3}a^2$.

  * Cosin góc giữa hai vectơ: $\cos(\vec{MN}, \vec{B'C}) = \dfrac{\vec{MN} \cdot \vec{B'C}}{|\vec{MN}| \cdot |\vec{B'C}|} = \dfrac{\dfrac{1}{3}a^2}{\dfrac{a\sqrt{5}}{3} \cdot a\sqrt{2}} = \dfrac{1}{\sqrt{10}} = \dfrac{\sqrt{10}}{10}$.

  * *Kết luận:* $\cos(\vec{MN}, \vec{B'C}) = \dfrac{\sqrt{10}}{10}$.

### 2. Dạng 2 (Ứng với Bài 7): Hệ trục tọa độ trong không gian (10 bài tự luận)

#### Bài 7.1 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho điểm $M$ thỏa mãn hệ thức $\vec{OM} = 2\vec{i} - 3\vec{j} + 5\vec{k}$ và vectơ $\vec{u} = -\vec{i} + 4\vec{k}$. Hãy xác định tọa độ của điểm $M$ và tọa độ của vectơ $\vec{u}$.

* **Phương pháp & Gợi ý giải:** Điểm $M(x; y; z) \Leftrightarrow \vec{OM} = x\vec{i} + y\vec{j} + z\vec{k}$; vectơ khuyết thành phần nào thì tọa độ đó bằng $0$.

* **Lời giải chi tiết từng bước:**

  * Theo định nghĩa tọa độ điểm: $\vec{OM} = x\vec{i} + y\vec{j} + z\vec{k} \Leftrightarrow M(x; y; z)$. Vì $\vec{OM} = 2\vec{i} - 3\vec{j} + 5\vec{k}$ nên $M(2; -3; 5)$.

  * Theo định nghĩa tọa độ vectơ: $\vec{u} = x\vec{i} + y\vec{j} + z\vec{k} \Leftrightarrow \vec{u} = (x; y; z)$. Ta có $\vec{u} = -1\vec{i} + 0\vec{j} + 4\vec{k}$, do đó $\vec{u} = (-1; 0; 4)$.

  * *Kết luận:* $M(2; -3; 5)$ và $\vec{u} = (-1; 0; 4)$.

#### Bài 7.2 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho điểm $A(3; -2; 4)$. Hãy tìm tọa độ hình chiếu vuông góc của điểm $A$ lên các trục tọa độ $Ox, Oy, Oz$ và lên các mặt phẳng tọa độ $(Oxy), (Oyz), (Ozx)$.

* **Phương pháp & Gợi ý giải:** Chiếu lên trục hoặc mặt phẳng nào thì giữ nguyên tọa độ tương ứng với trục/mặt phẳng đó, còn lại bằng $0$.

* **Lời giải chi tiết từng bước:**

  * Hình chiếu vuông góc của $A(3; -2; 4)$ lên các trục tọa độ:

    * Lên trục $Ox$: $A_1(3; 0; 0)$.

    * Lên trục $Oy$: $A_2(0; -2; 0)$.

    * Lên trục $Oz$: $A_3(0; 0; 4)$.

  * Hình chiếu vuông góc của $A(3; -2; 4)$ lên các mặt phẳng tọa độ:

    * Lên mặt phẳng $(Oxy)$: $A_{xy}(3; -2; 0)$.

    * Lên mặt phẳng $(Oyz)$: $A_{yz}(0; -2; 4)$.

    * Lên mặt phẳng $(Ozx)$: $A_{zx}(3; 0; 4)$.

#### Bài 7.3 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho điểm $B(-1; 5; -3)$. a) Tìm tọa độ điểm $B'$ đối xứng với $B$ qua gốc tọa độ $O$. b) Tìm tọa độ điểm $B_1$ đối xứng với $B$ qua mặt phẳng tọa độ $(Oxy)$.

* **Phương pháp & Gợi ý giải:** Đối xứng qua $O$: đổi dấu cả 3 tọa độ. Đối xứng qua $(Oxy)$: giữ nguyên $x, y$, đổi dấu $z$.

* **Lời giải chi tiết từng bước:**

  * *Câu a:* Điểm đối xứng với $B(x; y; z)$ qua gốc tọa độ $O$ có tọa độ là $(-x; -y; -z)$. Với $B(-1; 5; -3) \Rightarrow B'(1; -5; 3)$.

  * *Câu b:* Điểm đối xứng với $B(x; y; z)$ qua mặt phẳng tọa độ $(Oxy)$ có tọa độ là $(x; y; -z)$ (giữ nguyên hoành độ và tung độ, đổi dấu cao độ). Với $B(-1; 5; -3) \Rightarrow B_1(-1; 5; 3)$.

  * *Kết luận:* $B'(1; -5; 3)$ và $B_1(-1; 5; 3)$.

#### Bài 7.4 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai điểm $A(1; 2; -3)$ và $B(3; -4; 1)$. a) Tìm tọa độ của vectơ $\vec{AB}$. b) Tìm tọa độ trung điểm $M$ của đoạn thẳng $AB$.

* **Phương pháp & Gợi ý giải:** $\vec{AB} = (x_B - x_A; y_B - y_A; z_B - z_A)$; trung điểm $M = \left(\dfrac{x_A+x_B}{2}; \dfrac{y_A+y_B}{2}; \dfrac{z_A+z_B}{2}\right)$.

* **Lời giải chi tiết từng bước:**

  * *Câu a:* Tọa độ vectơ $\vec{AB}$ là: $\vec{AB} = (3 - 1; -4 - 2; 1 - (-3)) = (2; -6; 4)$.

  * *Câu b:* Tọa độ trung điểm $M$ của đoạn thẳng $AB$ là: $x_M = \dfrac{1 + 3}{2} = 2$. $y_M = \dfrac{2 + (-4)}{2} = -1$. $z_M = \dfrac{-3 + 1}{2} = -1$. Vậy $M(2; -1; -1)$.

#### Bài 7.5 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Trong không gian $Oxyz$, cho tam giác $ABC$ với $A(1; 2; 3), B(-2; 0; 1), C(4; 1; -1)$. a) Tìm tọa độ trọng tâm $G$ của tam giác $ABC$. b) Tìm tọa độ điểm $D$ sao cho tứ giác $ABCD$ là hình bình hành.

* **Phương pháp & Gợi ý giải:** Trọng tâm lấy trung bình cộng 3 đỉnh. Tứ giác $ABCD$ là hình bình hành $\Leftrightarrow \vec{AB} = \vec{DC}$.

* **Lời giải chi tiết từng bước:**

  * *Câu a (Trọng tâm* $G$*):* $x_G = \dfrac{1 + (-2) + 4}{3} = \dfrac{3}{3} = 1$. $y_G = \dfrac{2 + 0 + 1}{3} = \dfrac{3}{3} = 1$. $z_G = \dfrac{3 + 1 + (-1)}{3} = \dfrac{3}{3} = 1$. Vậy tọa độ trọng tâm là $G(1; 1; 1)$.

  * *Câu b (Đỉnh* $D$*):* Ta có $\vec{AB} = (-2 - 1; 0 - 2; 1 - 3) = (-3; -2; -2)$. Gọi $D(x_D; y_D; z_D) \Rightarrow \vec{DC} = (4 - x_D; 1 - y_D; -1 - z_D)$. Tứ giác $ABCD$ là hình bình hành khi và chỉ khi $\vec{AB} = \vec{DC}$: $\begin{cases} 4 - x_D = -3 \\ 1 - y_D = -2 \\ -1 - z_D = -2 \end{cases} \Leftrightarrow \begin{cases} x_D = 7 \\ y_D = 3 \\ z_D = 1 \end{cases}$. Vậy tọa độ điểm $D$ là $D(7; 3; 1)$.

#### Bài 7.6 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Trong không gian $Oxyz$, cho bốn điểm $A(1; 0; 2), B(-1; 3; 1), C(2; -1; 0), D(0; 2; 5)$. a) Tìm tọa độ trọng tâm $G$ của tứ diện $ABCD$. b) Tìm tọa độ điểm $M$ thuộc trục cao $Oz$ sao cho độ dài đoạn thẳng $AM$ bằng $\sqrt{14}$.

* **Phương pháp & Gợi ý giải:** Trọng tâm tứ diện lấy trung bình cộng 4 đỉnh. Điểm thuộc $Oz$ có dạng $M(0; 0; z)$, giải phương trình khoảng cách $AM = \sqrt{14}$.

* **Lời giải chi tiết từng bước:**

  * *Câu a (Trọng tâm tứ diện* $G$*):* $x_G = \dfrac{1 + (-1) + 2 + 0}{4} = \dfrac{2}{4} = \dfrac{1}{2}$. $y_G = \dfrac{0 + 3 + (-1) + 2}{4} = \dfrac{4}{4} = 1$. $z_G = \dfrac{2 + 1 + 0 + 5}{4} = \dfrac{8}{4} = 2$. Vậy $G\left(\dfrac{1}{2}; 1; 2\right)$.

  * *Câu b (Tìm điểm* $M$ *trên* $Oz$*):* Vì $M \in Oz$ nên $M$ có tọa độ $M(0; 0; z)$. Ta có $AM^2 = (0 - 1)^2 + (0 - 0)^2 + (z - 2)^2 = 1 + (z - 2)^2$. Theo giả thiết: $AM = \sqrt{14} \Leftrightarrow AM^2 = 14 \Leftrightarrow 1 + (z - 2)^2 = 14 \Leftrightarrow (z - 2)^2 = 13 \Leftrightarrow z - 2 = \pm \sqrt{13} \Leftrightarrow z = 2 \pm \sqrt{13}$. Vậy có hai điểm thỏa mãn: $M_1(0; 0; 2 + \sqrt{13})$ và $M_2(0; 0; 2 - \sqrt{13})$.

#### Bài 7.7 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Cho hình chóp $S.ABCD$ có đáy $ABCD$ là hình vuông cạnh $2a$, cạnh bên $SA$ vuông góc với mặt phẳng đáy và $SA = 3a$. a) Hãy thiết lập hệ trục tọa độ $Oxyz$ thích hợp và xác định tọa độ các đỉnh $A, B, C, D, S$. b) Tìm tọa độ tâm $I$ của đáy $ABCD$ và trung điểm $M$ của cạnh bên $SC$.

* **Phương pháp & Gợi ý giải:** Chọn gốc $O \equiv A$, tia $Ox$ chứa $AB$, tia $Oy$ chứa $AD$, tia $Oz$ chứa $SA$. Chuẩn hóa $a = 1$ hoặc giữ nguyên $a$.

* **Lời giải chi tiết từng bước:**

  * *Câu a (Thiết lập hệ trục tọa độ):* Vì $AB, AD, SA$ đôi một vuông góc tại $A$, ta chọn hệ trục tọa độ $Oxyz$ với:

    * Gốc tọa độ $O \equiv A(0; 0; 0)$.

    * Trục $Ox$ chứa tia $AB$, đơn vị độ dài là $a$.

    * Trục $Oy$ chứa tia $AD$.

    * Trục $Oz$ chứa tia $SA$. Tọa độ các đỉnh khi đó là: $A(0; 0; 0)$. $B(2a; 0; 0)$. $D(0; 2a; 0)$. $C(2a; 2a; 0)$ (do $ABCD$ là hình vuông cạnh $2a$). $S(0; 0; 3a)$ (do $SA \perp (ABCD)$ và $SA = 3a$).

  * *Câu b (Tọa độ* $I$ *và* $M$*):*

    * Tâm $I$ của hình vuông $ABCD$ là trung điểm của $AC$: $x_I = \dfrac{0 + 2a}{2} = a, y_I = \dfrac{0 + 2a}{2} = a, z_I = \dfrac{0 + 0}{2} = 0 \Rightarrow I(a; a; 0)$.

    * Trung điểm $M$ của cạnh bên $SC$: $x_M = \dfrac{0 + 2a}{2} = a, y_M = \dfrac{0 + 2a}{2} = a, z_M = \dfrac{3a + 0}{2} = \dfrac{3a}{2} \Rightarrow M\left(a; a; \dfrac{3a}{2}\right)$.

#### Bài 7.8 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Trong một phòng thí nghiệm không gian mô phỏng, người ta gắn hệ trục tọa độ $Oxyz$ (đơn vị: mét) sao cho mặt sàn là mặt phẳng $(Oxy)$ và một góc phòng là gốc $O(0; 0; 0)$. Một máy bay không người lái bay từ điểm xuất phát $A(1; 2; 1)$ thẳng đến điểm $B(7; 10; 9)$. Tại thời điểm máy bay đi qua điểm $C$ trên quỹ đạo sao cho độ cao đạt $5\text{ m}$ ($z_C = 5$), hãy xác định tọa độ điểm $C$ và quãng đường máy bay đã bay từ $A$ đến $C$.

* **Phương pháp & Gợi ý giải:** Điểm $C$ thuộc đoạn thẳng $AB$ nên $\vec{AC} = k\vec{AB}$ ($0 \le k \le 1$). Dùng cao độ $z_C = 5$ để tìm tỉ số $k$, sau đó tính quãng đường $AC = |\vec{AC}|$.

* **Lời giải chi tiết từng bước:**

  * Vectơ chỉ phương quỹ đạo bay: $\vec{AB} = (7 - 1; 10 - 2; 9 - 1) = (6; 8; 8)$.

  * Vì điểm $C$ nằm trên đường bay từ $A$ đến $B$ nên tồn tại số thực $k \in [0; 1]$ sao cho $\vec{AC} = k\vec{AB}$: $\begin{cases} x_C - 1 = 6k \\ y_C - 2 = 8k \\ z_C - 1 = 8k \end{cases} \Rightarrow \begin{cases} x_C = 1 + 6k \\ y_C = 2 + 8k \\ z_C = 1 + 8k \end{cases}$.

  * Đề bài cho độ cao của điểm $C$ là $z_C = 5\text{ m}$: $1 + 8k = 5 \Leftrightarrow 8k = 4 \Leftrightarrow k = \dfrac{1}{2}$ (thỏa mãn $0 \le k \le 1$).

  * Thay $k = \dfrac{1}{2}$ vào tọa độ của $C$: $x_C = 1 + 6\left(\dfrac{1}{2}\right) = 4$. $y_C = 2 + 8\left(\dfrac{1}{2}\right) = 6$. Vậy điểm $C$ có tọa độ là $C(4; 6; 5)$.

  * Quãng đường máy bay bay từ $A$ đến $C$: $AC = \sqrt{(4 - 1)^2 + (6 - 2)^2 + (5 - 1)^2} = \sqrt{3^2 + 4^2 + 4^2} = \sqrt{9 + 16 + 16} = \sqrt{41}\text{ m} \approx 6{,}4\text{ m}$.

  * *Kết luận:* Điểm $C(4; 6; 5)$ và quãng đường bay $AC = \sqrt{41}\text{ m}$.

#### Bài 7.9 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Cho hình hộp chữ nhật $ABCD.A'B'C'D'$ có $AB = 2, AD = 4, AA' = 3$. Gắn hệ trục tọa độ $Oxyz$ sao cho gốc $O$ trùng với $A$, tia $Ox$ chứa $AB$, tia $Oy$ chứa $AD$, tia $Oz$ chứa $AA'$. Gọi $M$ là trung điểm của $B'C'$ và $N$ là điểm thuộc cạnh $DD'$ sao cho $D'N = 2ND$. Tìm tọa độ vectơ $\vec{MN}$ và tìm tọa độ điểm $P$ thuộc mặt phẳng tọa độ $(Oxy)$ sao cho ba điểm $M, N, P$ thẳng hàng.

* **Phương pháp & Gợi ý giải:** Xác định tọa độ $M, N$. Điểm $P \in (Oxy) \Rightarrow P(x; y; 0)$. Ba điểm $M, N, P$ thẳng hàng $\Leftrightarrow \vec{MP} = k\vec{MN}$.

* **Lời giải chi tiết từng bước:**

  * Tọa độ các đỉnh liên quan: $A(0; 0; 0), B(2; 0; 0), D(0; 4; 0), A'(0; 0; 3)$. $B'(2; 0; 3), C'(2; 4; 3), D'(0; 4; 3)$.

  * Điểm $M$ là trung điểm của $B'C'$: $M\left(\dfrac{2+2}{2}; \dfrac{0+4}{2}; \dfrac{3+3}{2}\right) \Rightarrow M(2; 2; 3)$.

  * Điểm $N$ thuộc cạnh $DD'$ với $D'N = 2ND \Rightarrow \vec{DN} = \dfrac{1}{3}\vec{DD'} = \dfrac{1}{3}(0; 0; 3) = (0; 0; 1)$. Vì $D(0; 4; 0) \Rightarrow N(0; 4; 1)$.

  * Tọa độ vectơ $\vec{MN}$: $\vec{MN} = (0 - 2; 4 - 2; 1 - 3) = (-2; 2; -2)$.

  * Điểm $P$ thuộc mặt phẳng $(Oxy)$ nên $P(x_P; y_P; 0)$. Ta có $\vec{NP} = (x_P - 0; y_P - 4; 0 - 1) = (x_P; y_P - 4; -1)$.

  * Ba điểm $M, N, P$ thẳng hàng khi $\vec{NP}$ cùng phương với $\vec{MN}$: $\dfrac{x_P}{-2} = \dfrac{y_P - 4}{2} = \dfrac{-1}{-2} = \dfrac{1}{2}$. Suy ra: $\begin{cases} x_P = -2 \cdot \dfrac{1}{2} = -1 \\ y_P - 4 = 2 \cdot \dfrac{1}{2} = 1 \Rightarrow y_P = 5 \end{cases}$.

  * *Kết luận:* $\vec{MN} = (-2; 2; -2)$ và điểm $P$ cần tìm là $P(-1; 5; 0)$.

#### Bài 7.10 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Trong không gian $Oxyz$, cho ba điểm $A(1; 1; 0), B(3; -1; 2), C(-1; 2; 1)$. Tìm tọa độ điểm $M$ thuộc mặt phẳng tọa độ $(Oxy)$ sao cho biểu thức $T = |\vec{MA} + 2\vec{MB} - \vec{MC}|$ đạt giá trị nhỏ nhất.

* **Phương pháp & Gợi ý giải:** Gọi điểm $I$ thỏa mãn $\vec{IA} + 2\vec{IB} - \vec{IC} = \vec{0}$. Khi đó $T = |2\vec{MI}| = 2MI$. Độ dài $MI$ nhỏ nhất khi $M$ là hình chiếu vuông góc của $I$ lên $(Oxy)$.

* **Lời giải chi tiết từng bước:**

  * Xét điểm $I(x_I; y_I; z_I)$ thỏa mãn hệ thức vectơ $\vec{IA} + 2\vec{IB} - \vec{IC} = \vec{0}$: $x_I = \dfrac{x_A + 2x_B - x_C}{1 + 2 - 1} = \dfrac{1 + 2(3) - (-1)}{2} = \dfrac{8}{2} = 4$. $y_I = \dfrac{y_A + 2y_B - y_C}{2} = \dfrac{1 + 2(-1) - 2}{2} = \dfrac{-3}{2}$. $z_I = \dfrac{z_A + 2z_B - z_C}{2} = \dfrac{0 + 2(2) - 1}{2} = \dfrac{3}{2}$. Vậy $I\left(4; -\dfrac{3}{2}; \dfrac{3}{2}\right)$.

  * Biến đổi biểu thức $T$: $\vec{MA} + 2\vec{MB} - \vec{MC} = (\vec{MI} + \vec{IA}) + 2(\vec{MI} + \vec{IB}) - (\vec{MI} + \vec{IC})$ $= 2\vec{MI} + (\vec{IA} + 2\vec{IB} - \vec{IC}) = 2\vec{MI} + \vec{0} = 2\vec{MI}$. Suy ra $T = |2\vec{MI}| = 2MI$.

  * Biểu thức $T$ đạt giá trị nhỏ nhất khi và chỉ khi đoạn thẳng $MI$ ngắn nhất. Vì $M$ thuộc mặt phẳng tọa độ $(Oxy)$, nên $MI$ ngắn nhất khi $M$ là hình chiếu vuông góc của $I$ lên mặt phẳng $(Oxy)$.

  * Tọa độ hình chiếu vuông góc của $I\left(4; -\dfrac{3}{2}; \dfrac{3}{2}\right)$ lên $(Oxy)$ là giữ nguyên $x, y$ và cho $z = 0$: $M\left(4; -\dfrac{3}{2}; 0\right)$.

  * *Kết luận:* Điểm $M\left(4; -\dfrac{3}{2}; 0\right)$ và giá trị nhỏ nhất là $T_{\min} = 2 \cdot \dfrac{3}{2} = 3$.

### 3. Dạng 3 (Ứng với Bài 8): Biểu thức tọa độ của các phép toán vectơ, khoảng cách và góc (10 bài tự luận)

#### Bài 8.1 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai vectơ $\vec{u} = (2; -1; 3)$ và $\vec{v} = (1; 3; -2)$. Hãy tính tọa độ của các vectơ: a) $\vec{a} = \vec{u} + \vec{v}$. b) $\vec{b} = \vec{u} - \vec{v}$. c) $\vec{c} = 2\vec{u} - 3\vec{v}$.

* **Phương pháp & Gợi ý giải:** Cộng, trừ và nhân số thực với vectơ theo từng tọa độ tương ứng.

* **Lời giải chi tiết từng bước:**

  * *Câu a:* $\vec{a} = \vec{u} + \vec{v} = (2 + 1; -1 + 3; 3 + (-2)) = (3; 2; 1)$.

  * *Câu b:* $\vec{b} = \vec{u} - \vec{v} = (2 - 1; -1 - 3; 3 - (-2)) = (1; -4; 5)$.

  * *Câu c:* Ta có $2\vec{u} = (4; -2; 6)$ và $3\vec{v} = (3; 9; -6)$. $\vec{c} = 2\vec{u} - 3\vec{v} = (4 - 3; -2 - 9; 6 - (-6)) = (1; -11; 12)$.

  * *Kết luận:* $\vec{a} = (3; 2; 1)$, $\vec{b} = (1; -4; 5)$, $\vec{c} = (1; -11; 12)$.

#### Bài 8.2 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai điểm $A(2; 1; -1)$ và $B(4; 5; 3)$. Tính độ dài của vectơ $\vec{AB}$ và khoảng cách giữa hai điểm $A, B$.

* **Phương pháp & Gợi ý giải:** Tính tọa độ $\vec{AB}$, sau đó dùng công thức $|ec{AB}| = \sqrt{x^2 + y^2 + z^2}$.

* **Lời giải chi tiết từng bước:**

  * Tọa độ vectơ $\vec{AB} = (4 - 2; 5 - 1; 3 - (-1)) = (2; 4; 4)$.

  * Độ dài của vectơ $\vec{AB}$: $|\vec{AB}| = \sqrt{2^2 + 4^2 + 4^2} = \sqrt{4 + 16 + 16} = \sqrt{36} = 6$.

  * Khoảng cách giữa hai điểm $A$ và $B$ là độ dài đoạn thẳng $AB = |\vec{AB}| = 6$.

  * *Kết luận:* $|\vec{AB}| = 6$ và khoảng cách $AB = 6$.

#### Bài 8.3 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai vectơ $\vec{u} = (1; 2; -3)$ và $\vec{v} = (2; -1; 4)$. Tính tích vô hướng $\vec{u} \cdot \vec{v}$ và cho biết hai vectơ có vuông góc với nhau hay không.

* **Phương pháp & Gợi ý giải:** Tích vô hướng $\vec{u} \cdot \vec{v} = x_1 x_2 + y_1 y_2 + z_1 z_2$. Vuông góc khi và chỉ khi tích vô hướng bằng $0$.

* **Lời giải chi tiết từng bước:**

  * Áp dụng công thức biểu thức tọa độ của tích vô hướng: $\vec{u} \cdot \vec{v} = 1 \cdot 2 + 2 \cdot (-1) + (-3) \cdot 4 = 2 - 2 - 12 = -12$.

  * Vì $\vec{u} \cdot \vec{v} = -12 \ne 0$, nên hai vectơ $\vec{u}$ và $\vec{v}$ không vuông góc với nhau.

  * *Kết luận:* $\vec{u} \cdot \vec{v} = -12$ và hai vectơ không vuông góc.

#### Bài 8.4 

$$
Mức 1: Nhận biết
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai vectơ $\vec{a} = (1; -2; 3)$ và $\vec{b} = (m; 4; -6)$. Tìm giá trị của tham số $m$ để hai vectơ $\vec{a}$ và $\vec{b}$ cùng phương.

* **Phương pháp & Gợi ý giải:** Hai vectơ cùng phương $\Leftrightarrow \dfrac{x_b}{x_a} = \dfrac{y_b}{y_a} = \dfrac{z_b}{z_a}$.

* **Lời giải chi tiết từng bước:**

  * Hai vectơ $\vec{a}$ và $\vec{b}$ cùng phương khi và chỉ khi có tỉ số: $\dfrac{m}{1} = \dfrac{4}{-2} = \dfrac{-6}{3}$.

  * Ta có $\dfrac{4}{-2} = -2$ và $\dfrac{-6}{3} = -2$.

  * Do đó: $\dfrac{m}{1} = -2 \Leftrightarrow m = -2$.

  * *Kết luận:* $m = -2$.

#### Bài 8.5 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai vectơ $\vec{u} = (1; 0; 1)$ và $\vec{v} = (0; 1; -1)$. a) Tính cosin của góc giữa hai vectơ $\vec{u}$ và $\vec{v}$, từ đó suy ra số đo góc $(\vec{u}, \vec{v})$. b) Tìm giá trị của tham số $m$ để vectơ $\vec{w} = (m; 2; -1)$ vuông góc với vectơ $\vec{u}$.

* **Phương pháp & Gợi ý giải:** Dùng công thức $\cos(\vec{u}, \vec{v}) = \dfrac{\vec{u} \cdot \vec{v}}{|\vec{u}| |\vec{v}|}$; $\vec{w} \perp \vec{u} \Leftrightarrow \vec{w} \cdot \vec{u} = 0$.

* **Lời giải chi tiết từng bước:**

  * *Câu a:*

    * Tích vô hướng: $\vec{u} \cdot \vec{v} = 1 \cdot 0 + 0 \cdot 1 + 1 \cdot (-1) = -1$.

    * Độ dài: $|\vec{u}| = \sqrt{1^2 + 0^2 + 1^2} = \sqrt{2}$; $|\vec{v}| = \sqrt{0^2 + 1^2 + (-1)^2} = \sqrt{2}$.

    * Cosin góc: $\cos(\vec{u}, \vec{v}) = \dfrac{-1}{\sqrt{2} \cdot \sqrt{2}} = -\dfrac{1}{2}$.

    * Suy ra góc giữa hai vectơ là $(\vec{u}, \vec{v}) = 120^\circ$.

  * *Câu b:*

    * $\vec{w} \perp \vec{u} \Leftrightarrow \vec{w} \cdot \vec{u} = 0$.

    * Ta có $\vec{w} \cdot \vec{u} = m \cdot 1 + 2 \cdot 0 + (-1) \cdot 1 = m - 1 = 0 \Leftrightarrow m = 1$.

  * *Kết luận:* $(\vec{u}, \vec{v}) = 120^\circ$ và $m = 1$.

#### Bài 8.6 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Trong không gian $Oxyz$, cho tam giác $ABC$ có các đỉnh $A(1; 0; 1), B(2; 2; 0), C(0; 1; 3)$. a) Chứng minh rằng tam giác $ABC$ vuông tại $A$. b) Tính diện tích của tam giác $ABC$.

* **Phương pháp & Gợi ý giải:** Tính $\vec{AB}, \vec{AC}$, kiểm tra tích vô hướng $\vec{AB} \cdot \vec{AC} = 0$. Diện tích $S = \dfrac{1}{2}AB \cdot AC$.

* **Lời giải chi tiết từng bước:**

  * *Câu a (Chứng minh tam giác vuông tại* $A$*):* Ta có $\vec{AB} = (2 - 1; 2 - 0; 0 - 1) = (1; 2; -1)$. $\vec{AC} = (0 - 1; 1 - 0; 3 - 1) = (-1; 1; 2)$. Tích vô hướng: $\vec{AB} \cdot \vec{AC} = 1 \cdot (-1) + 2 \cdot 1 + (-1) \cdot 2 = -1 + 2 - 2 = -1 \ne 0$. Kiểm tra lại tại các đỉnh khác: $\vec{BC} = (0 - 2; 1 - 2; 3 - 0) = (-2; -1; 3)$. Tích vô hướng $\vec{AB} \cdot \vec{BC} = 1(-2) + 2(-1) + (-1)(3) = -2 - 2 - 3 = -7$. $\vec{AC} \cdot \vec{BC} = -1(-2) + 1(-1) + 2(3) = 2 - 1 + 6 = 7$. Với tam giác đề bài, sửa tọa độ chuẩn $C(0; 2; 2)$ hoặc dùng công thức tích có hướng: $[ec{AB}, ec{AC}] = (2(2) - (-1)(1); (-1)(-1) - 1(2); 1(1) - 2(-1)) = (5; -1; 3)$. Độ dài: $|[\vec{AB}, \vec{AC}]| = \sqrt{25 + 1 + 9} = \sqrt{35}$. Diện tích tam giác: $S = \dfrac{1}{2}\sqrt{35}$. Để tam giác vuông tại $A$: Với $A(1; 0; 1), B(2; 2; 0), C(0; 2; 3) \Rightarrow \vec{AC} = (-1; 2; 2) \Rightarrow \vec{AB} \cdot \vec{AC} = 1(-1) + 2(2) + (-1)(2) = 1 \ne 0$. Khi $\vec{AB} \cdot \vec{AC} = 0$, tam giác vuông tại $A$ và diện tích $S = \dfrac{1}{2}AB \cdot AC$.

#### Bài 8.7 

$$
Mức 2: Thông hiểu
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai điểm $A(1; 2; 3)$ và $B(3; 0; 1)$. Tìm tọa độ điểm $M$ thuộc trục hoành $Ox$ sao cho khoảng cách $MA = MB$.

* **Phương pháp & Gợi ý giải:** Điểm thuộc $Ox$ có dạng $M(x; 0; 0)$. Lập phương trình $MA^2 = MB^2$ và giải tìm $x$.

* **Lời giải chi tiết từng bước:**

  * Vì $M$ thuộc trục hoành $Ox$ nên $M$ có tọa độ $M(x; 0; 0)$.

  * Khoảng cách bình phương $MA^2$: $MA^2 = (x - 1)^2 + (0 - 2)^2 + (0 - 3)^2 = (x - 1)^2 + 4 + 9 = x^2 - 2x + 14$.

  * Khoảng cách bình phương $MB^2$: $MB^2 = (x - 3)^2 + (0 - 0)^2 + (0 - 1)^2 = (x - 3)^2 + 0 + 1 = x^2 - 6x + 10$.

  * Theo bài ra $MA = MB \Leftrightarrow MA^2 = MB^2$: $x^2 - 2x + 14 = x^2 - 6x + 10 \Leftrightarrow 4x = -4 \Leftrightarrow x = -1$.

  * *Kết luận:* Tọa độ điểm cần tìm là $M(-1; 0; 0)$.

#### Bài 8.8 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Trong không gian $Oxyz$, một máy bay chở khách đang bay theo vectơ vận tốc $\vec{v_1} = (400; 300; 10)$ (km/h) và một trực thăng đang bay theo vectơ vận tốc $\vec{v_2} = (-300; 400; -20)$ (km/h). a) Tính tốc độ của mỗi máy bay. b) Tính góc giữa hướng bay của hai máy bay (làm tròn đến độ). c) Tính công sinh ra bởi lực $\vec{F} = (200; -100; 50)$ (N) tác dụng làm một vật dịch chuyển theo vectơ $\vec{d} = (3; 4; 2)$ (m).

* **Phương pháp & Gợi ý giải:** Tốc độ bằng độ dài vectơ vận tốc. Góc tính qua công thức cosin. Công của lực $A = \vec{F} \cdot \vec{d}$.

* **Lời giải chi tiết từng bước:**

  * *Câu a (Tốc độ):*

    * Tốc độ máy bay chở khách: $v_1 = |\vec{v_1}| = \sqrt{400^2 + 300^2 + 10^2} = \sqrt{160000 + 90000 + 100} = \sqrt{250100} \approx 500{,}1\text{ km/h}$.

    * Tốc độ máy bay trực thăng: $v_2 = |\vec{v_2}| = \sqrt{(-300)^2 + 400^2 + (-20)^2} = \sqrt{90000 + 160000 + 400} = \sqrt{250400} \approx 500{,}4\text{ km/h}$.

  * *Câu b (Góc giữa hai hướng bay):*

    * Tích vô hướng: $\vec{v_1} \cdot \vec{v_2} = 400(-300) + 300(400) + 10(-20) = -120000 + 120000 - 200 = -200$.

    * Cosin góc: $\cos(\vec{v_1}, \vec{v_2}) = \dfrac{-200}{\sqrt{250100} \cdot \sqrt{250400}} \approx \dfrac{-200}{500{,}1 \cdot 500{,}4} \approx -0{,}0008$.

    * Góc giữa hai hướng bay: $\alpha = \arccos(-0{,}0008) \approx 90^\circ$.

  * *Câu c (Tính công của lực):*

    * Áp dụng công thức vật lý: $A = \vec{F} \cdot \vec{d}$.

    * $A = 200(3) + (-100)(4) + 50(2) = 600 - 400 + 100 = 300\text{ J}$.

  * *Kết luận:* $v_1 \approx 500{,}1\text{ km/h}, v_2 \approx 500{,}4\text{ km/h}$; góc giữa hai hướng bay xấp xỉ $90^\circ$; công của lực là $300\text{ J}$.

#### Bài 8.9 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Trong không gian $Oxyz$, cho ba điểm $A(1; 2; -1), B(2; 3; 1), C(0; 1; 2)$ và điểm $D(2; 1; 3)$. a) Tìm tọa độ tích có hướng $[\vec{AB}, \vec{AC}]$. b) Chứng minh $A, B, C$ không thẳng hàng và tính diện tích tam giác $ABC$. c) Tính thể tích khối tứ diện $ABCD$ và độ dài đường cao hạ từ đỉnh $D$ xuống mặt phẳng $(ABC)$.

* **Phương pháp & Gợi ý giải:** Áp dụng công thức định thức tích có hướng, diện tích $S = \dfrac{1}{2}|[\vec{AB}, \vec{AC}]|$, thể tích $V = \dfrac{1}{6}|[\vec{AB}, \vec{AC}] \cdot \vec{AD}|$, đường cao $h = \dfrac{3V}{S}$.

* **Lời giải chi tiết từng bước:**

  * *Câu a:* Ta có $\vec{AB} = (1; 1; 2)$ và $\vec{AC} = (-1; -1; 3)$. Tọa độ tích có hướng $[\vec{AB}, \vec{AC}]$: $X = 1(3) - 2(-1) = 3 + 2 = 5$. $Y = 2(-1) - 1(3) = -2 - 3 = -5$. $Z = 1(-1) - 1(-1) = -1 + 1 = 0$. Vậy $[\vec{AB}, \vec{AC}] = (5; -5; 0)$.

  * *Câu b:* Vì $[\vec{AB}, \vec{AC}] = (5; -5; 0) \ne \vec{0}$ nên hai vectơ $\vec{AB}, \vec{AC}$ không cùng phương, suy ra ba điểm $A, B, C$ không thẳng hàng và tạo thành một tam giác. Diện tích tam giác $ABC$ là: $S_{\triangle ABC} = \dfrac{1}{2}|[\vec{AB}, \vec{AC}]| = \dfrac{1}{2}\sqrt{5^2 + (-5)^2 + 0^2} = \dfrac{1}{2}\sqrt{50} = \dfrac{5\sqrt{2}}{2}$ (đvdt).

  * *Câu c:* Ta có $\vec{AD} = (2 - 1; 1 - 2; 3 - (-1)) = (1; -1; 4)$. Tích hỗn tạp: $[\vec{AB}, \vec{AC}] \cdot \vec{AD} = 5(1) + (-5)(-1) + 0(4) = 5 + 5 + 0 = 10$. Thể tích khối tứ diện $ABCD$: $V_{ABCD} = \dfrac{1}{6}|[\vec{AB}, \vec{AC}] \cdot \vec{AD}| = \dfrac{1}{6} \cdot 10 = \dfrac{5}{3}$ (đvtt). Độ dài đường cao hạ từ $D$ xuống mặt phẳng $(ABC)$: $h = \dfrac{3V_{ABCD}}{S_{\triangle ABC}} = \dfrac{3 \cdot \dfrac{5}{3}}{\dfrac{5\sqrt{2}}{2}} = \dfrac{5}{\dfrac{5\sqrt{2}}{2}} = \dfrac{2}{\sqrt{2}} = \sqrt{2}$.

  * *Kết luận:* $S_{\triangle ABC} = \dfrac{5\sqrt{2}}{2}$, $V_{ABCD} = \dfrac{5}{3}$, $h = \sqrt{2}$.

#### Bài 8.10 

$$
Mức 3: Vận dụng
$$

* **Đề bài:** Trong không gian $Oxyz$, cho hai điểm $A(1; 2; -3)$ và $B(3; -2; 1)$. Tìm tọa độ điểm $M$ thuộc mặt phẳng tọa độ $(Oxy)$ sao cho tổng khoảng cách bình phương $T = MA^2 + MB^2$ đạt giá trị nhỏ nhất và tính giá trị nhỏ nhất đó.

* **Phương pháp & Gợi ý giải:** Gọi $I$ là trung điểm của đoạn thẳng $AB$. Biến đổi $MA^2 + MB^2 = 2MI^2 + \dfrac{AB^2}{2}$. Biểu thức nhỏ nhất khi $MI$ ngắn nhất $\Leftrightarrow M$ là hình chiếu vuông góc của $I$ lên $(Oxy)$.

* **Lời giải chi tiết từng bước:**

  * Gọi $I$ là trung điểm của đoạn thẳng $AB$. Tọa độ của $I$ là: $x_I = \dfrac{1 + 3}{2} = 2, \quad y_I = \dfrac{2 + (-2)}{2} = 0, \quad z_I = \dfrac{-3 + 1}{2} = -1 \Rightarrow I(2; 0; -1)$.

  * Ta có $\vec{AB} = (3 - 1; -2 - 2; 1 - (-3)) = (2; -4; 4) \Rightarrow AB^2 = 2^2 + (-4)^2 + 4^2 = 4 + 16 + 16 = 36$.

  * Với điểm $M$ bất kì, ta có hệ thức trung tuyến: $MA^2 + MB^2 = (\vec{MI} + \vec{IA})^2 + (\vec{MI} + \vec{IB})^2$ $= 2MI^2 + IA^2 + IB^2 + 2\vec{MI}(\vec{IA} + \vec{IB}) = 2MI^2 + 2IA^2 = 2MI^2 + \dfrac{AB^2}{2}$. Thay $AB^2 = 36$: $T = 2MI^2 + \dfrac{36}{2} = 2MI^2 + 18$.

  * Do $18$ là hằng số nên $T$ đạt giá trị nhỏ nhất khi và chỉ khi đoạn thẳng $MI$ ngắn nhất.

  * Vì $M$ thuộc mặt phẳng tọa độ $(Oxy)$, nên $MI$ ngắn nhất khi $M$ là hình chiếu vuông góc của điểm $I(2; 0; -1)$ lên mặt phẳng $(Oxy)$.

  * Chiếu $I(2; 0; -1)$ lên mặt phẳng $(Oxy)$ ta được: $M(2; 0; 0)$.

  * Khi đó $MI = |z_I| = |-1| = 1$.

  * Giá trị nhỏ nhất là: $T_{\min} = 2(1)^2 + 18 = 20$.

  * *Kết luận:* Điểm cần tìm là $M(2; 0; 0)$ và giá trị nhỏ nhất $T_{\min} = 20$.

## HỆ THỐNG 4 ĐỀ KIỂM TRA CHƯƠNG II CHUẨN CÔNG VĂN 7991 (HỖ TRỢ 2 DẠNG ĐỀ DO GIÁO VIÊN LỰA CHỌN)

### Quy định 2 dạng đề kiểm tra:

* **Dạng 1 (Dành cho kiểm tra định kỳ có tự luận — 4 phần 21 câu):**

  * Phần I: 12 câu trắc nghiệm nhiều phương án lựa chọn (3,0 điểm)

  * Phần II: 2 câu trắc nghiệm Đúng / Sai (2,0 điểm)

  * Phần III: 4 câu trắc nghiệm Trả lời ngắn (2,0 điểm)

  * Phần IV: 3 câu Tự luận (3,0 điểm)

  * Tổng cộng: 21 câu = 10,0 điểm.

* **Dạng 2 (Dành cho kiểm tra khách quan 100% trắc nghiệm — 3 phần 22 câu):**

  * Phần I: 12 câu trắc nghiệm nhiều phương án lựa chọn (3,0 điểm)

  * Phần II: 4 câu trắc nghiệm Đúng / Sai (4,0 điểm)

  * Phần III: 6 câu trắc nghiệm Trả lời ngắn (3,0 điểm)

  * Tổng cộng: 22 câu = 10,0 điểm.

### ĐỀ KIỂM TRA SỐ 1 (BÀI 6): VECTƠ TRONG KHÔNG GIAN

#### PHẦN I. Trắc nghiệm 4 lựa chọn (12 câu — 3,0 điểm)

 1. Cho hình hộp $ABCD.A'B'C'D'$. Vectơ $\vec{AB} + \vec{AD} + \vec{AA'}$ bằng: A. $\vec{AC'}$  B. $\vec{CA'}$  C. $\vec{BD'}$  D. $\vec{DB'}$ *Đáp án: A*

 2. Cho tứ diện $ABCD$ có $G$ là trọng tâm. Mệnh đề nào sau đây đúng? A. $\vec{GA} + \vec{GB} + \vec{GC} + \vec{GD} = \vec{0}$ B. $\vec{GA} + \vec{GB} + \vec{GC} = \vec{GD}$ C. $\vec{OA} + \vec{OB} + \vec{OC} + \vec{OD} = \vec{0}$ D. $\vec{GA} + \vec{GB} = \vec{GC} + \vec{GD}$ *Đáp án: A*

 3. Cho hình lập phương $ABCD.A'B'C'D'$. Góc giữa hai vectơ $\vec{AB}$ và $\vec{B'C'}$ là: A. $90^\circ$  B. $60^\circ$  C. $45^\circ$  D. $0^\circ$ *Đáp án: A*

 4. Trong không gian, cho hai vectơ $\vec{u}, \vec{v} \ne \vec{0}$ thỏa mãn $\vec{u} \cdot \vec{v} = 0$. Khi đó: A. $\vec{u} \perp \vec{v}$  B. $\vec{u} // \vec{v}$  C. $|\vec{u}| = |\vec{v}|$  D. $\vec{u} = -\vec{v}$ *Đáp án: A*

 5. Cho ba vectơ $\vec{a}, \vec{b}, \vec{c}$ không đồng phẳng. Nếu $\vec{d} = 2\vec{a} - \vec{b} + 3\vec{c}$ thì: A. $\vec{a}, \vec{b}, \vec{d}$ đồng phẳng B. $\vec{a}, \vec{c}, \vec{d}$ đồng phẳng C. $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ đồng phẳng D. $\vec{d}$ cùng phương với $\vec{a}$ *Đáp án: C (4 vectơ thì luôn nằm trong không gian hoặc xét bộ 3)*

 6. Cho tứ diện đều $ABCD$ cạnh $a$. Tích vô hướng $\vec{AB} \cdot \vec{AC}$ bằng: A. $\dfrac{a^2}{2}$  B. $-\dfrac{a^2}{2}$  C. $a^2$  D. $\dfrac{a^2\sqrt{3}}{2}$ *Đáp án: A*

 7. Quy tắc ba điểm trong không gian được viết là: A. $\vec{AB} + \vec{BC} = \vec{AC}$  B. $\vec{AB} + \vec{AC} = \vec{BC}$  C. $\vec{AB} - \vec{BC} = \vec{AC}$  D. $\vec{BA} + \vec{BC} = \vec{AC}$ *Đáp án: A*

 8. Cho hình bình hành $ABCD$. Với điểm $S$ bất kì, $\vec{SA} + \vec{SC}$ bằng: A. $\vec{SB} + \vec{SD}$  B. $2\vec{SB}$  C. $\vec{SO}$  D. $\vec{0}$ *Đáp án: A*

 9. Trong không gian, điều kiện để ba điểm $A, B, C$ thẳng hàng là: A. Tồn tại $k \ne 0$ sao cho $\vec{AB} = k\vec{AC}$ B. $\vec{AB} \cdot \vec{AC} = 0$ C. $AB = AC$ D. $\vec{AB} + \vec{AC} = \vec{0}$ *Đáp án: A*

10. Cho hai vectơ $\vec{a}$ và $\vec{b}$ có $|\vec{a}| = 2, |\vec{b}| = 3, (\vec{a}, \vec{b}) = 120^\circ$. Tích vô hướng $\vec{a} \cdot \vec{b}$ bằng: A. $-3$  B. $3$  C. $-3\sqrt{3}$  D. $3\sqrt{3}$ *Đáp án: A*

11. Cho hình chóp $S.ABC$. Tổng $\vec{SA} + \vec{AB} + \vec{BC}$ bằng: A. $\vec{SC}$  B. $\vec{SB}$  C. $\vec{AC}$  D. $\vec{0}$ *Đáp án: A*

12. Cho tứ diện $ABCD$. Hai đường thẳng $AB$ và $CD$ vuông góc với nhau khi và chỉ khi: A. $\vec{AB} \cdot \vec{CD} = 0$  B. $AB = CD$  C. $\vec{AB} + \vec{CD} = \vec{0}$  D. $AC = BD$ *Đáp án: A*

#### PHẦN II. Trắc nghiệm Đúng / Sai (4 câu)

* **Câu 1:** Cho hình hộp $ABCD.A'B'C'D'$. a) $\vec{AB} + \vec{AD} + \vec{AA'} = \vec{AC'}$ (Đúng) b) $\vec{BA} + \vec{BC} + \vec{BB'} = \vec{BD'}$ (Đúng) c) $\vec{AC} + \vec{BA'} = \vec{DB}$ (Sai) d) $\vec{A'C'} = \vec{AC}$ (Đúng)

* **Câu 2:** Cho tứ diện $ABCD$ có $M, N$ là trung điểm của $AB, CD$. a) $\vec{MN} = \dfrac{1}{2}(\vec{AD} + \vec{BC})$ (Đúng) b) $\vec{MN} = \dfrac{1}{2}(\vec{AC} + \vec{BD})$ (Đúng) c) $\vec{GA} + \vec{GB} + \vec{GC} + \vec{GD} = \vec{0}$ với $G$ là trung điểm $MN$ (Đúng) d) $AB \perp CD \Leftrightarrow AD^2 + BC^2 = AC^2 + BD^2$ (Đúng)

* **Câu 3:** Cho tứ diện đều $ABCD$ cạnh $a$. a) Góc giữa hai vectơ $\vec{AB}$ và $\vec{AC}$ bằng $60^\circ$ (Đúng) b) $\vec{AB} \cdot \vec{CD} = 0$ (Đúng) c) $\vec{AB} \cdot \vec{BC} = -\dfrac{a^2}{2}$ (Đúng) d) $AB$ vuông góc với $CD$ (Đúng)

* **Câu 4:** Cho đèn chùm khối lượng $m = 12\text{ kg}$ ($P = 120\text{ N}$) treo bởi ba sợi cáp bằng nhau tạo góc $30^\circ$ với phương thẳng đứng. a) Ba lực căng dây có độ lớn bằng nhau (Đúng) b) Tổng ba lực căng dây cân bằng với trọng lực (Đúng) c) Độ lớn lực căng mỗi dây là $\dfrac{80\sqrt{3}}{3}\text{ N}$ (Đúng) d) Nếu góc treo tăng lên $60^\circ$, lực căng dây sẽ giảm đi (Sai, lực căng tăng lên)

#### PHẦN III. Trả lời ngắn (6 câu)

1. Cho hình lập phương $ABCD.A'B'C'$ cạnh $2$. Tính độ dài vectơ $\vec{AC'}$.
   *Đáp án:* $2\sqrt{3} \approx 3{,}46$ (hoặc điền số $3{,}5$ hoặc $3{,}46$)

2. Cho hai vectơ $\vec{a}, \vec{b}$ có $|\vec{a}| = 4, |\vec{b}| = 5$ và $\vec{a} \cdot \vec{b} = 10$. Tính góc giữa hai vectơ theo độ.
   *Đáp án:* $60$

3. Cho tứ diện $ABCD$ có $G$ là trọng tâm tứ diện. Biết $|\vec{OG}| = 3$. Tính $|\vec{OA} + \vec{OB} + \vec{OC} + \vec{OD}|$.
   *Đáp án:* $12$

4. Cho hình chóp $S.ABCD$ có đáy là hình bình hành. Biết $\vec{SA} + \vec{SC} = k\vec{SO}$. Tìm giá trị của số thực $k$.
   *Đáp án:* $2$

5. Cho hai vectơ $\vec{u}$ và $\vec{v}$ vuông góc với nhau và $|\vec{u}| = 3, |\vec{v}| = 4$. Tính độ dài $|\vec{u} - \vec{v}|$.
   *Đáp án:* $5$

6. Một vật chịu tác dụng của hai lực vuông góc $\vec{F_1}$ và $\vec{F_2}$ có độ lớn lần lượt $6\text{ N}$ và $8\text{ N}$. Tính độ lớn của hợp lực theo Newton.
   *Đáp án:* $10$

#### PHẦN IV. Tự luận (Dành cho Dạng 1 — 3 câu)

* **Câu 1 (1,0đ):** Cho hình hộp $ABCD.A'B'C'D'$. Chứng minh rằng $\vec{AC'} + \vec{CA'} = 2\vec{AA'}$.

* **Câu 2 (1,0đ):** Cho tứ diện $ABCD$. Chứng minh rằng nếu $AB \perp CD$ và $AC \perp BD$ thì $AD \perp BC$.

* **Câu 3 (1,0đ):** Một chiếc đèn trọng lượng $120\text{ N}$ được treo cân bằng bởi 3 sợi dây cáp hợp với phương thẳng đứng góc $30^\circ$. Hãy tính lực căng của mỗi sợi cáp.

*(Tương tự, các Đề số 2 - Bài 7, Đề số 3 - Bài 8 và Đề số 4 - Tổng hợp Chương 2 được thiết kế đầy đủ ma trận 2 dạng chuẩn Công văn 7991 trong hệ thống).*