# SCRIPT THUYẾT TRÌNH PA3 — PAPER PROTOTYPE & FORMATIVE TESTING
## Freestyle Chess Mobile Web — Nhóm 06

**Môn:** CSC13112 — Thiết kế UI/UX · ThS. Phạm Nguyễn Sơn Tùng  
**Thời lượng:** ~10 phút (5 người × ~2 phút)  
**Ghi chú:** Slide bằng tiếng Anh, script bằng tiếng Việt. Người thuyết trình nói theo ý, không đọc nguyên văn.

---

## 👤 NGƯỜI 1: GIỚI THIỆU & BỐI CẢNH (~2 phút)

### 📌 Slide 1 — Title Slide
> **[Cue: Slide hiển thị tiêu đề PA3, tên nhóm]**

"Xin chào thầy và các bạn, nhóm 06 xin trình bày **Project Assignment 3** — phần **Paper Prototype và Formative Testing** cho sản phẩm **Freestyle Chess Mobile Web**.

Trong PA này, nhóm đã thiết kế các bản paper prototype bằng tay, sau đó tiến hành kiểm thử định hình với người dùng thực tế để đánh giá trước khi chuyển sang hi-fi prototype ở PA4."

**→ Chuyển slide**

---

### 📌 Slide 2 — Agenda
> **[Cue: Slide hiển thị 5 phần nội dung]**

"Bài thuyết trình hôm nay gồm 5 phần chính:
1. Nhắc lại vấn đề từ PA2 và phương pháp tiếp cận
2. **Task 1** — giải quyết vấn đề điều hướng bằng một tay
3. **Task 2** — giải quyết vấn đề tra cứu lịch thi đấu
4. **Formative Testing** — kế hoạch, quy trình và kết quả kiểm thử
5. **Kết luận** — chọn phương án tốt nhất và cải tiến cho PA4."

**→ Chuyển slide**

---

### 📌 Slide 3 — Problem Recap from PA2
> **[Cue: Slide hiển thị 2 problem cards]**

"Từ kết quả nghiên cứu người dùng ở PA2, nhóm đã xác định **2 vấn đề ưu tiên cao nhất**:

**Thứ nhất, P-01 — Navigation:** Nút hamburger menu nằm ở góc trên bên trái gây khó khăn cho người dùng khi thao tác bằng một tay, đặc biệt là khi đang di chuyển.

**Thứ hai, P-05 — Schedule:** Trang lịch thi đấu hiện tại thiếu nhiều thông tin quan trọng như danh sách kỳ thủ, chi tiết cặp đấu, và sơ đồ giải."

**→ Chuyển slide**

---

### 📌 Slide 4 — Our Approach
> **[Cue: Slide hiển thị 2×3 = 6 prototypes]**

"Để giải quyết, nhóm thiết kế **2 kịch bản kiểm thử**, mỗi kịch bản có **3 phương án paper prototype** khác nhau — tổng cộng **6 bản prototype vẽ tay** trên giấy trắng.

Nhóm cũng tạo một **phone case bằng giấy** để mô phỏng điện thoại thật khi test, và áp dụng **Think-Aloud Protocol** để thu thập phản hồi từ người dùng.

Bây giờ xin mời [Tên Người 2] trình bày chi tiết Task 1."

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 2: TASK 1 — NAVIGATION BAR (~2 phút)

### 📌 Slide 5 — Task 1 Overview
> **[Cue: Slide hiển thị scenario + ảnh phone case & home]**

"Task 1 tập trung vào vấn đề **điều hướng bằng một tay**. Kịch bản đặt ra là: người dùng vừa đi bộ vừa dùng điện thoại bằng một tay — chỉ sử dụng ngón cái — muốn chuyển từ trang Home sang trang Schedule.

Các bạn có thể thấy ảnh **phone case** mà nhóm đã làm từ giấy để mô phỏng môi trường test thực tế."

**→ Chuyển slide**

---

### 📌 Slide 6 — Variant 1: Fixed Bottom Nav Bar
> **[Cue: Slide hiển thị ảnh nav_1.JPG bên phải]**

"Phương án đầu tiên là **Bottom Navigation Bar cố định** — thanh tab nằm ở đáy màn hình gồm Home, Schedule, Videos, News, và More.

Ưu điểm lớn nhất: người dùng chỉ cần **1 lần chạm** để chuyển trang. Tất cả tab đều nằm trong **vùng với của ngón cái** — reachability rất cao, cognitive load thấp vì các mục hiện sẵn."

**→ Chuyển slide**

---

### 📌 Slide 7 — Variant 2: FAB Menu
> **[Cue: Slide hiển thị ảnh nav_2.JPG — radial menu components]**

"Phương án 2 dùng **Floating Action Button** — nút tròn nổi ở góc dưới bên phải. Khi bấm, menu xòe ra dạng hình tròn hoặc danh sách dọc.

Cần **2 lần chạm**: lần 1 mở menu, lần 2 chọn Schedule. Ưu điểm là không chiếm không gian màn hình khi không sử dụng, nhưng cần thêm một bước để thấy được các mục điều hướng."

**→ Chuyển slide**

---

### 📌 Slide 8 — Variant 3: Bottom Hamburger
> **[Cue: Slide hiển thị ảnh nav_3_menu.JPG — full-screen menu]**

"Phương án 3 giữ nguyên hamburger menu nhưng **chuyển xuống đáy màn hình** — giải quyết trực tiếp vấn đề P-01. Khi bấm, menu full-screen overlay mở ra với đầy đủ tất cả danh mục giống như web gốc.

Cũng cần **2 lần chạm**, nhưng ưu điểm là giữ được toàn bộ menu items của bản web hiện tại.

Bây giờ xin mời [Tên Người 3] trình bày Task 2."

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 3: TASK 2 — SCHEDULE (~2 phút)

### 📌 Slide 9 — Task 2 Overview
> **[Cue: Slide hiển thị scenario + 3 variant cards]**

"Task 2 giải quyết vấn đề **tra cứu chi tiết lịch đấu**. Kịch bản: một người hâm mộ cờ vua muốn tìm lại thông tin danh sách kỳ thủ của giải đấu đã diễn ra, hoặc xem chi tiết cặp đấu cụ thể.

Nhóm cũng thiết kế **3 phương án** cho task này."

**→ Chuyển slide**

---

### 📌 Slide 10 — Variant 1: Accordion Cards
> **[Cue: Slide hiển thị 2 ảnh: collapsed vs expanded]**

"Phương án 1 dùng **Accordion/Collapsible Cards**. Trang Schedule chia thành 2 phần: **SOON** (giải sắp tới) hiển thị đầy đủ, và **PREVIOUS** (giải đã qua) thu gọn với icon mũi tên.

Khi người dùng bấm vào thẻ, nó **mở rộng tại chỗ** hiển thị thêm danh sách Players. Không cần chuyển trang — nhanh và quen thuộc."

**→ Chuyển slide**

---

### 📌 Slide 11 — Variant 2: Date Filter + Detail Page
> **[Cue: Slide hiển thị 2 ảnh: filter view + match detail]**

"Phương án 2 dùng **bộ lọc ngày tháng** ở trên cùng — dropdown Tháng, Năm và dải chọn Ngày. Mỗi thẻ trận đấu có nút **Detail →** dẫn đến trang chi tiết riêng.

Như các bạn thấy trong ảnh bên phải — trang detail hiển thị **cặp đấu L.Q.Liem vs Magnus Carlsen**, kèm rating GM, và bàn cờ phân tích. Đây là phương án có **thông tin chi tiết nhất** nhưng cần nhiều bước thao tác hơn."

**→ Chuyển slide**

---

### 📌 Slide 12 — Variant 3: Vertical Timeline
> **[Cue: Slide hiển thị ảnh timeline với vạch đỏ Today]**

"Phương án cuối cùng là **Vertical Interactive Timeline** — trục thời gian dọc với vạch đỏ **Today** ở giữa. Vuốt lên để xem giải quá khứ, vuốt xuống để xem giải tương lai.

Đây là phương án **trực quan nhất** — trải nghiệm cuộn 2 chiều rất mượt mà và dễ hiểu. Tuy nhiên, lượng thông tin hiển thị ở mức vừa đủ."

**→ Chuyển slide**

---

### 📌 Slide 13 — Comparison Table
> **[Cue: Slide hiển thị 2 bảng so sánh]**

"Slide này tổng hợp **bảng so sánh** cho cả 2 Task.

Với **Task 1**: Phương án Bottom Nav Bar nổi bật nhất về số lượt chạm — chỉ 1 tap — và cognitive load thấp.

Với **Task 2**: Phương án Date Filter + Detail Page cung cấp thông tin đầy đủ nhất, trong khi Accordion nhanh nhất, và Timeline độc đáo nhất về trải nghiệm.

Xin mời [Tên Người 4] trình bày phần Formative Testing."

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 4: FORMATIVE TESTING (~2 phút)

### 📌 Slide 14 — Testing Plan
> **[Cue: Slide hiển thị mục tiêu, đối tượng, phương pháp, metrics]**

"Nhóm xây dựng **kế hoạch kiểm thử định hình** với các yếu tố sau:

**Mục tiêu:** Đánh giá khả năng sử dụng của 6 bản lo-fi prototype trước khi tạo hi-fi.

**Đối tượng:** 2-3 người tham gia chưa biết gì về prototype.

**Phương pháp:** Paper Prototype Testing kết hợp **Think-Aloud Protocol** — người dùng nói ra suy nghĩ khi thao tác.

**Chỉ số đo lường** gồm: số lượt chạm, thời gian hoàn thành, lỗi/ngập ngừng, và phản hồi định tính."

**→ Chuyển slide**

---

### 📌 Slide 15 — Testing Procedure & Roles
> **[Cue: Slide hiển thị 3 role cards + số liệu tổng quan]**

"Trong mỗi phiên test, nhóm phân công **3 vai trò**:

**Facilitator** — đọc kịch bản, hướng dẫn quy trình, khuyến khích người dùng think aloud.

**Computer** — đứng trước các mảnh giấy prototype, khi người dùng chạm vào nút thì **tráo mảnh giấy** để mô phỏng phản hồi hệ thống. Không được nói gì.

**Observer** — đếm tap, đo thời gian, quay phim, ghi chép mọi sự cố.

Tổng cộng nhóm thực hiện **6 vòng test**: 2 task × 3 variant, với mỗi người tham gia."

**→ Chuyển slide**

---

### 📌 Slide 16 — Testing Results [PLACEHOLDER]
> **[Cue: Slide hiển thị placeholder boxes]**

"Slide này dành cho **kết quả kiểm thử** — hiện tại nhóm đang trong quá trình tiến hành test *(hoặc: nhóm đã hoàn thành test, kết quả như sau...)*

Phần **Quantitative Data** bao gồm bảng so sánh số liệu tập trung, thời gian và tỉ lệ lỗi cho từng phương án.

Phần **Qualitative Feedback** ghi nhận các quan sát, điểm pain point và phản hồi tích cực từ người dùng.

Xin mời [Tên Người 5] trình bày phần kết luận."

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 5: KẾT LUẬN & CẢI TIẾN (~2 phút)

### 📌 Slide 17 — Best Variant Selection [PLACEHOLDER]
> **[Cue: Slide hiển thị placeholder cho 2 kết quả + improvements]**

"Dựa trên kết quả formative testing, nhóm đã chọn:

**Task 1 — Navigation:** *(điền phương án được chọn)* vì... *(lý do dựa trên dữ liệu test)*

**Task 2 — Schedule:** *(điền phương án được chọn)* vì... *(lý do dựa trên dữ liệu test)*

Nhóm cũng xác định các **điểm cần cải thiện** cho PA4, bao gồm...
*(liệt kê các improvement points sau khi test)*"

**→ Chuyển slide**

---

### 📌 Slide 18 — Thank You & Q&A
> **[Cue: Slide hiển thị Thank You + thông tin nhóm]**

"Đó là toàn bộ nội dung PA3 của nhóm 06. Tóm lại, nhóm đã:
- Thiết kế **6 paper prototype** cho 2 kịch bản trọng tâm
- Xây dựng **kế hoạch kiểm thử định hình** theo chuẩn Think-Aloud
- Tiến hành test và xác định phương án tốt nhất

Bước tiếp theo ở **PA4**, nhóm sẽ phát triển prototype được chọn thành **hi-fi prototype** trên máy tính.

Cảm ơn thầy và các bạn đã lắng nghe. Nhóm xin nhận phản hồi và câu hỏi ạ!"

---

## 📋 GHI CHÚ CHO NGƯỜI THUYẾT TRÌNH

| Chuyển mục | Ai → Ai | Cue chuyển |
|------------|---------|------------|
| Slide 4 → 5 | Người 1 → Người 2 | "Bây giờ xin mời [Tên] trình bày Task 1" |
| Slide 8 → 9 | Người 2 → Người 3 | "Xin mời [Tên] trình bày Task 2" |
| Slide 13 → 14 | Người 3 → Người 4 | "Xin mời [Tên] trình bày phần Formative Testing" |
| Slide 16 → 17 | Người 4 → Người 5 | "Xin mời [Tên] trình bày phần kết luận" |

### Tips:
- **Điều khiển slide:** Dùng phím **→** hoặc **Space** để chuyển slide tiếp, **←** để quay lại
- **Không đọc slide:** Slide bằng tiếng Anh, bạn nói tiếng Việt theo ý — KHÔNG dịch từng chữ
- **Chỉ vào ảnh:** Khi nói về paper prototype, hãy chỉ tay vào ảnh trên slide để minh họa
- **Thời gian:** Mỗi người ~2 phút, tổng không quá 10 phút
- **Placeholder slides (16, 17):** Cập nhật nội dung sau khi hoàn thành formative testing
