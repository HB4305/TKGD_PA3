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

### 📌 Slide 5 — Task 1 Overview & Storyboard
> **[Cue: Slide hiển thị 4 khung tranh sketch vẽ tay: Khung 1 (Đi bộ) → Khung 2 (Ngón tay với menu trên suýt rơi máy) → Khung 3 (Ý tưởng đưa xuống đáy) → Khung 4 (Thao tác 1 tay mượt mà)]**

"Task 1 tập trung giải quyết bài toán **điều hướng bằng một tay khi đang di chuyển**. Nhóm đã xây dựng câu chuyện qua 4 khung tranh phác thảo trên slide:

- **Khung 1 (Bối cảnh):** Bạn **Ninh**, 22 tuổi, đang vừa đi bộ trên khuôn viên vừa cầm điện thoại bằng tay phải để mở trang web Freestyle Chess.
- **Khung 2 (Nỗi đau P-01):** Khi Ninh cố với ngón cái lên tận góc trên bên trái để bấm nút Hamburger `[≡]`, ngón tay bị quá tầm với, chiếc điện thoại nghiêng ngả suýt rơi khỏi tay.
- **Khung 3 (Động lực):** Ninh nhận ra cần phải chuyển toàn bộ hệ thống điều hướng xuống **vùng đáy màn hình** — nơi ngón tay cái nghỉ tự nhiên và dễ với nhất.
- **Khung 4 (Kết quả):** Nhờ đưa menu xuống đáy, Ninh có thể vừa bước đi vừa chuyển trang Lịch đấu chỉ với 1 chạm cực kỳ an toàn và thoải mái.

Để hiện thực hóa kịch bản này, nhóm đề xuất **3 phương án Paper Prototype** mà tôi sẽ trình bày ngay sau đây."

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

### 📌 Slide 9 — Task 2 Overview & Storyboard
> **[Cue: Slide hiển thị 4 khung tranh sketch vẽ tay: Khung 1 (Tranh luận ở cafe) → Khung 2 (Web cũ thiếu thông tin P-05) → Khung 3 (Ý tưởng phân tầng & timeline) → Khung 4 (Tra cứu thành công trong vài giây)]**

"Task 2 giải quyết vấn đề **tra cứu chi tiết lịch đấu và danh sách kỳ thủ**. Câu chuyện được minh họa qua 4 khung tranh:

- **Khung 1 (Bối cảnh):** Bạn **Phú** và bạn của mình đang ngồi cà phê tranh luận sôi nổi về một ván đấu cờ vua trong quá khứ và quyết định mở web để kiểm chứng.
- **Khung 2 (Nỗi đau P-05):** Khi mở bản web cũ, màn hình chỉ hiện đúng ngày và tên giải chung chung — hoàn toàn không có danh sách kỳ thủ, không có chi tiết cặp đấu hay tỷ số. Cả hai đều bối rối!
- **Khung 3 (Động lực):** Động lực thiết kế đặt ra là cần cấu trúc dữ liệu phân cấp rõ ràng: phân tách giải sắp tới và giải đã qua, đồng thời hỗ trợ xem nhanh tại chỗ hoặc qua trục thời gian.
- **Khung 4 (Kết quả):** Với thiết kế mới, Phú và bạn có thể tra cứu ngay danh sách kỳ thủ (Lê Quang Liêm vs Magnus Carlsen) và kết quả trận đấu chỉ trong vài giây.

Sau đây là **3 phương án Paper Prototype** mà nhóm đã phát triển để giải quyết bài toán này."

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

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 4: FORMATIVE TESTING (~2 phút)

### 📌 Slide 13 — Testing Plan
> **[Cue: Slide hiển thị mục tiêu, đối tượng người tham gia, phương pháp test và dữ liệu định tính thu thập]**

"Nhóm xây dựng **kế hoạch kiểm thử định hình (Formative Testing)** với các yếu tố sau:

**Mục tiêu:** Đánh giá khả năng sử dụng của 6 bản lo-fi prototype trước khi phát triển bản hi-fi.

**Đối tượng:** 3 người tham gia (18–25 tuổi, sinh viên đại học) chưa có kiến thức trước về các mô hình prototype.

**Phương pháp:** Paper Prototype Testing kết hợp **Think-Aloud Protocol** — ghi nhận toàn bộ dữ liệu định tính gồm quan sát hành vi, phản hồi và các điểm cải tiến."

**→ Chuyển slide**

---

### 📌 Slide 14 — Testing Procedure & Roles
> **[Cue: Slide hiển thị 3 role cards + số liệu tổng quan]**

"Trong mỗi phiên test, nhóm phân công **3 vai trò**:

**Facilitator** — đọc kịch bản, hướng dẫn quy trình, khuyến khích người dùng think aloud.

**Mobile (Computer Role)** — thao tác mô hình điện thoại giấy, khi người dùng chạm vào nút thì **tráo mảnh giấy màn hình/menu** để mô phỏng phản hồi của ứng dụng di động. Không được nói gì.

**Observer** — quan sát và ghi chép toàn bộ dữ liệu định tính: các cử chỉ ngập ngừng, điểm gây bối rối, phản hồi bằng lời và quay video để phân tích định tính.

Tổng cộng nhóm thực hiện **6 vòng test**: 2 task × 3 variant, với mỗi người tham gia."

**→ Chuyển slide**

---

### 📌 Slide 15 — Task Behavioral Observations
> **[Cue: Slide hiển thị 2 khối quan sát hành vi cho Task 1 và Task 2]**

"Tiếp theo, về **quan sát hành vi thực tế (Behavioral Observations)** qua 6 vòng test:

- **Với Task 1 (Navigation Bar):** Khi vừa đi bộ vừa cầm máy 1 tay, người dùng chạm ngay vào tab ở đáy **(Bottom Nav - V1)** một cách vô thức và an toàn. Với **FAB (V2)**, người dùng bị ngập ngừng mất 1–2 giây để tìm nút. Còn với **Bottom Hamburger (V3)**, menu mở tràn toàn màn hình gây mất ngữ cảnh đọc.

- **Với Task 2 (Schedule Lookup):** Người dùng hiểu ngay icon `▼` trên thẻ **Accordion (V1)** để mở danh sách kỳ thủ tại chỗ. Với **Date Filter (V2)**, người dùng rất thích bàn cờ phân tích ở trang chi tiết nhưng nhận xét các bước lọc Dropdown hơi tốn công. Còn với **Timeline (V3)**, người dùng phải cuộn màn hình lên nhiều lần mới tìm thấy các giải đấu trong quá khứ."

**→ Chuyển slide**

---

### 📌 Slide 16 — User Feedback & Usability Breakdowns
> **[Cue: Slide hiển thị trích dẫn phản hồi Think-Aloud và 4 sự cố nhận thức chính]**

"Về **phản hồi định tính và các sự cố nhận thức (Breakdowns)**:

- **Ý kiến phản hồi trực tiếp (Think-Aloud):** Người dùng đánh giá rất cao sự tiện lợi của thanh Bottom Nav vì ngón cái nghỉ tự nhiên khi di chuyển, đồng thời phản hồi tích cực với giao diện bàn cờ phân tích trận đấu chuyên nghiệp trên trang chi tiết.

- **Các sự cố nhận thức phát hiện (Breakdowns):**
  1. Nút FAB ẩn chứa menu làm người dùng phải thử-sai để khám phá.
  2. Overlay toàn màn hình gây ngắt đứt dòng đọc (Context Loss).
  3. Lượng thông tin hiển thị bị quá tải khi mở rộng thẻ.
  4. Thiếu thao tác tìm kiếm làm người dùng phải cuộn trang nhiều lần để tìm trận đấu cũ.

Bây giờ xin mời [Tên Người 5] trình bày phần lựa chọn phương án tốt nhất và định hướng cho PA4."

**→ Chuyển slide, chuyển người**

---

## 👤 NGƯỜI 5: KẾT LUẬN & CẢI TIẾN (~2 phút)

### 📌 Slide 17 — Best Variant Selection
> **[Cue: Slide hiển thị 2 thẻ phương án chiến thắng và 3 điểm cải tiến PA4 bên dưới]**

"Dựa trên toàn bộ dữ liệu thực nghiệm và phản hồi người dùng, nhóm 06 đưa ra quyết định thiết kế:

1. **Task 1 — Navigation:** Nhóm chọn **Variant 1 — Fixed Bottom Navigation Bar** làm giải pháp chính thức. Đây là phương án đạt tỷ lệ thành công 100%, thao tác 1 chạm trong vùng với tự nhiên của ngón cái, loại bỏ hoàn toàn nguy cơ trượt rơi máy.

2. **Task 2 — Schedule:** Nhóm quyết định chọn **Variant 2 — Date Filter + Detail Page** làm giải pháp chính thức. Phương án này tích hợp bộ lọc Tháng/Năm, dải ngày chọn nhanh và nút 'Detail →' dẫn sang trang chi tiết có bàn cờ phân tích chuyên sâu cho người hâm mộ.

3. **Hướng cải tiến cho PA4:** Nhóm xác định 3 trọng tâm cần tối ưu khi chuyển sang bản Hi-Fi Prototype:
   - **Thứ nhất:** Chuẩn hóa toàn bộ vùng bấm (touch target) đạt tối thiểu $48 \times 48\text{ px}$ theo tiêu chuẩn WCAG.
   - **Thứ hai:** Thêm hiệu ứng chuyển động mượt mà khi mở thẻ và chỉ báo trạng thái Active rõ ràng trên thanh tab.
   - **Thứ ba:** Bổ sung thanh tìm kiếm nhanh kỳ thủ và các thẻ tag phân loại giải đấu (Rapid, Blitz, Classic)."

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
- **Slides (16, 17):** Đã cập nhật đầy đủ số liệu kiểm thử định hình và phương án lựa chọn tối ưu cho PA4

