# ĐẶC TẢ STORYBOARD & KỊCH BẢN THỰC TẾ (PA3 - FREESTYLE CHESS MOBILE WEB)

**Môn học:** CSC13112 - Thiết kế UI/UX (TS. Lê Khánh Duy - ThS. Phạm Nguyễn Sơn Tùng)
**Nhóm thực hiện:** Nhóm 06
**Phạm vi sản phẩm:** Freestyle Chess Mobile Web (Smartphone Browser)
**Mục tiêu tài liệu:** Đặc tả chi tiết kịch bản Storyboard (Bối cảnh, Động lực, Nỗi đau người dùng, Tương tác giải pháp và Kết quả) tương ứng cho 2 Task Workflow và 6 phương án Paper Prototype. Tài liệu phục vụ vẽ tranh minh họa bằng tay trên giấy trắng, quay video YouTube và đưa vào báo cáo `GroupID-PA3-PaperProtype.pdf`.

---

## I. NGUYÊN TẮC VÀ CẤU TRÚC THIẾT KẾ STORYBOARD

Theo tiêu chuẩn thiết kế UI/UX và yêu cầu đề bài PA3:

- **Mục đích:** Minh họa trực quan câu chuyện người dùng trong thế giới thực (_Context of Use_), giải thích _Tại sao (Motivation)_ họ gặp vấn đề với thiết kế cũ và _Làm thế nào (How)_ các phương án Paper Prototype giải quyết được vấn đề đó.
- **Quy chuẩn vẽ tay:**
  - Vẽ từ **4 - 6 khung tranh** cho mỗi kịch bản.
  - Sử dụng bút mực / bút màu (không dùng bút chì), vẽ trên giấy trắng không dòng kẻ.
  - Có nhân vật (người que / nhân vật hoạt hình đơn giản), biểu cảm khuôn mặt, bóng thoại lời nói `[...]` và bóng thoại suy nghĩ `(...)`.
  - Có chú thích ngắn gọn (Caption) bên dưới mỗi khung hình.

---

## II. STORYBOARD 1: ĐIỀU HƯỚNG BẰNG MỘT TAY KHI ĐANG DI CHUYỂN (NAVIGATION TASK)

- **Vấn đề giải quyết (P-01):** Nút Hamburger Menu ở góc trên bên trái màn hình rất khó bấm bằng ngón tay cái khi người dùng chỉ cầm máy bằng một tay.
- **Persona đại diện:** Ninh (22 tuổi, sinh viên/nhân viên văn phòng, thường xuyên di chuyển bằng xe buýt hoặc đi bộ, hay theo dõi nhanh các ván đấu cờ vua trên điện thoại).

```
+-----------------------------------------------------------------------------------+
|                        TỔNG QUAN LUỒNG TRUYỆN STORYBOARD 1                        |
|                                                                                   |
|  [Khung 1: Bối cảnh]       [Khung 2: Vấn đề (P-01)]     [Khung 3: Nhu cầu/Động lực] |
|   Ninh đang đi bộ nhanh     Ngón cái với lên góc trên    "Ước gì menu nằm ở dưới   |
|   cầm máy bằng 1 tay        không tới, suýt rơi máy!     để bấm bằng 1 ngón cái!"  |
|                                                                                   |
|                                 | (Phân nhánh sang 3 giải pháp Paper Prototype)   |
|                                 v                                                 |
|  +-----------------------------------------------------------------------------+  |
|  | [Khung 4A: Fixed Bottom Nav] | [Khung 4B: FAB Radial Menu] | [Khung 4C: Bottom Ham] |
|  | 1 chạm vào tab Schedule ở đáy| Bấm nút tròn nổi góc phải   | Bấm 3 gạch ở đáy      |
|  +-----------------------------------------------------------------------------+  |
|                                 |                                                 |
|                                 v                                                 |
|                         [Khung 5: Kết quả & Cảm xúc]                              |
|                          Ninh xem ngay Lịch đấu dễ dàng                           |
|                          Vừa đi vừa lướt mượt mà, vui vẻ!                          |
+-----------------------------------------------------------------------------------+
```

---

### Chi tiết kịch bản từng khung hình Storyboard 1

#### 🖼️ Khung 1: Thiết lập bối cảnh (Setting the Scene)

- **Hình ảnh vẽ:** Ninh đang đi bộ trên vỉa hè / hành lang trường học. Tay phải cầm chiếc smartphone, mắt nhìn vào màn hình. Xung quanh vẽ vài nét gạch chuyển động biểu thị đang bước đi.
- **Bóng thoại / Suy nghĩ:** Ninh nghĩ: _"Trận chung kết Freestyle Chess hôm nay mấy giờ đánh nhỉ? Mở web xem thử."_
- **Chú thích (Caption):** Ninh đang vừa đi bộ vừa mở trang web Freestyle Chess bằng một tay.

#### 🖼️ Khung 2: Nỗi đau & Sự cố (Pain Point & Frustration - P-01)

- **Hình ảnh vẽ:** Khung hình phóng to bàn tay Ninh cầm điện thoại. Ngón tay cái cố vươn hết cỡ lên góc trên bên trái màn hình để chạm vào icon Hamburger `[≡]`. Bàn tay gượng gạo, mặt Ninh toát mồ hôi hột `(O_O;)`, chiếc điện thoại nghiêng ngả suýt trượt khỏi tay.
- **Bóng thoại:** Ninh thốt lên: _"Á! Xa quá, với ngón cái không tới... Cầm một tay thế này dễ rơi máy quá!"_
- **Chú thích (Caption):** Nút Hamburger ở góc trên-trái nằm ngoài vùng với tự nhiên của ngón cái (Hard-to-reach zone).

#### 🖼️ Khung 3: Động lực & Mong muốn (Motivation & Trigger)

- **Hình ảnh vẽ:** Ninh dừng lại một nhịp, nhìn vào khu vực đáy màn hình điện thoại (vùng ngón cái thoải mái nhất - Thumb Zone). Vẽ một bóng đèn phát sáng ý tưởng trên đầu Ninh.
- **Bóng thoại:** Ninh nghĩ: _"Phải chi thanh điều hướng nằm gọn ở cạnh dưới, chạm phát là tới luôn thì tiện biết mấy!"_
- **Chú thích (Caption):** Người dùng cần hệ thống điều hướng đặt ở đáy màn hình để thao tác 1 chạm thuận tiện.

---

#### 🖼️ Khung 4: Giải pháp tương tác (Resolution with Paper Prototype Variants)

_Nhóm vẽ 3 khung hình độc lập (4A, 4B, 4C) tương ứng với 3 phương án Paper Prototype:_

- **🔹 Nhánh 4A (Variant 1 - Fixed Bottom Navigation Bar):**
  - **Hình ảnh vẽ:** Cận cảnh màn hình điện thoại có thanh **Bottom Nav Bar** cố định ở đáy. Ngón cái của Ninh nhẹ nhàng chạm ngay vào icon `Schedule` (Lịch đấu). Màn hình lập tức đổi sang trang Schedule.
  - **Lời thoại:** Ninh cười: _"Chỉ 1 chạm ngay đáy màn hình, cực kỳ nhanh!"_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`nav_1.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/nav_1.JPG).

- **🔹 Nhánh 4B (Variant 2 - Floating Action Button Menu):**
  - **Hình ảnh vẽ:** Nút tròn nổi **FAB** nằm ở góc dưới bên phải. Ngón cái chạm vào FAB $\rightarrow$ một vòng tròn menu xòe ra $\rightarrow$ chạm chọn `Schedule`.
  - **Lời thoại:** Ninh nghĩ: _"Menu xòe gọn gàng ở góc phải, màn hình rộng rãi không bị vướng mắt."_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`nav_2.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/nav_2.JPG).

- **🔹 Nhánh 4C (Variant 3 - Bottom Hamburger Menu):**
  - **Hình ảnh vẽ:** Nút Hamburger `[≡]` được dời xuống góc dưới bên trái. Ninh chạm ngón cái vào đáy $\rightarrow$ mở ra màn hình menu lớn phủ kín dễ bấm.
  - **Lời thoại:** Ninh nói: _"Nút 3 gạch ở dưới bấm rất êm, danh mục hiện to rõ ràng!"_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`nav_3_menu.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/nav_3_menu.JPG).

---

#### 🖼️ Khung 5: Kết quả & Sự hài lòng (Outcome & Relief)

- **Hình ảnh vẽ:** Ninh tiếp tục bước đi tự tin, khuôn mặt tươi cười `(^__^)`, tay cầm điện thoại chắc chắn, trang Lịch đấu đã mở sẵn sàng trước mắt.
- **Bóng thoại:** Ninh mỉm cười: _"Tuyệt vời! Vừa đi vừa lướt xem lịch đấu êm ru chỉ bằng 1 tay."_
- **Chú thích (Caption):** Thao tác điều hướng một tay thành công trọn vẹn, nâng cao độ an toàn và sự tiện lợi khi di chuyển.

---

## III. STORYBOARD 2: TRA CỨU CHI TIẾT LỊCH ĐẤU & KỲ THỦ (SCHEDULE TASK)

- **Vấn đề giải quyết (P-05):** Trang Schedule cũ chỉ có tên giải và ngày tháng chung chung, thiếu danh sách kỳ thủ (`Players`), không có thông tin chi tiết cặp đấu quá khứ hay bàn cờ trực quan.
- **Persona đại diện:** Phú (20 tuổi, người hâm mộ cờ vua cuồng nhiệt, đang ngồi ở quán cà phê tranh luận với bạn về giải đấu cờ vua Freestyle Chess năm ngoái).

```
+-----------------------------------------------------------------------------------+
|                        TỔNG QUAN LUỒNG TRUYỆN STORYBOARD 2                        |
|                                                                                   |
|  [Khung 1: Bối cảnh]       [Khung 2: Vấn đề (P-05)]     [Khung 3: Nhu cầu/Động lực] |
|   Phú & bạn đang tranh luận Mở web cũ: Lịch chỉ có tên  "Ước gì có thể xem ngay ai  |
|   về giải đấu cờ vua cũ     ngày, không thấy kỳ thủ!    đấu với ai và xem bàn cờ!"  |
|                                                                                   |
|                                 | (Phân nhánh sang 3 giải pháp Paper Prototype)   |
|                                 v                                                 |
|  +-----------------------------------------------------------------------------+  |
|  | [Khung 4A: Accordion Cards] | [Khung 4B: Date Filter + Page]| [Khung 4C: Timeline]  |
|  | Chạm mở thẻ tại chỗ (v -> ^)| Chọn tháng/năm -> Detail page | Vuốt trục thời gian   |
|  | đọc danh sách Players ngay  | xem cặp đấu & bàn cờ phân tích| ngược về quá khứ      |
|  +-----------------------------------------------------------------------------+  |
|                                 |                                                 |
|                                 v                                                 |
|                         [Khung 5: Kết quả & Cảm xúc]                              |
|                          Phú tự tin chỉ cho bạn xem kết quả                        |
|                          Cả hai cùng hào hứng phân tích ván đấu!                  |
+-----------------------------------------------------------------------------------+
```

---

### Chi tiết kịch bản từng khung hình Storyboard 2

#### 🖼️ Khung 1: Thiết lập bối cảnh (Setting the Scene)

- **Hình ảnh vẽ:** Phú và người bạn đang ngồi uống nước tại quán cà phê, trên bàn có 2 ly nước. Bạn của Phú hào hứng hỏi: _"Này Phú, giải Freestyle Chess năm ngoái ở Đức có Lê Quang Liêm tham gia không nhỉ?"_
- **Bóng thoại:** Phú đáp: _"Để mình mở điện thoại kiểm tra danh sách kỳ thủ của giải đó ngay!"_
- **Chú thích (Caption):** Người dùng có nhu cầu tra cứu nhanh thông tin giải đấu và kỳ thủ đã thi đấu trong quá khứ.

#### 🖼️ Khung 2: Nỗi đau & Sự thiếu thốn thông tin (Pain Point - P-05)

- **Hình ảnh vẽ:** Phú nhìn vào màn hình web cũ. Màn hình chỉ hiện vỏn vẹn một dòng chữ thô sơ: _"2023 Germany Tournament - Ended"_. Hoàn toàn không có nút bấm xem thêm, không có danh sách người chơi, không có kết quả chi tiết. Phú nhíu mày thất vọng `(-_-;)`.
- **Bóng thoại:** Phú bực bội: _"Ủa? Chỉ ghi mỗi ngày với địa điểm thế này thì làm sao biết ai đã thi đấu?"_
- **Chú thích (Caption):** Giao diện cũ thiếu trầm trọng thông tin kỳ thủ tham gia (`Players`) và chi tiết cặp đấu.

#### 🖼️ Khung 3: Động lực thiết kế (Design Motivation)

- **Hình ảnh vẽ:** Phú chỉ tay vào màn hình, hình dung ra giao diện lịch đấu thông minh có thể mở rộng danh sách hoặc lọc tìm theo năm/tháng.
- **Bóng thoại:** Phú nghĩ: _"Phải có cách tra cứu trực quan: hoặc mở thẻ xem nhanh tại chỗ, hoặc lọc theo năm tháng để vào xem chi tiết trận đấu!"_
- **Chú thích (Caption):** Cần cấu trúc dữ liệu lịch đấu rõ ràng giữa các giải Sắp diễn ra (`SOON`) và Đã diễn ra (`PREVIOUS`).

---

#### 🖼️ Khung 4: Giải pháp tương tác (Resolution with Paper Prototype Variants)

_Nhóm vẽ 3 khung hình độc lập (4A, 4B, 4C) tương ứng với 3 phương án Paper Prototype:_

- **🔹 Nhánh 4A (Variant 1 - Accordion / Collapsible Cards):**
  - **Hình ảnh vẽ:** Phú cuộn xuống mục `PREVIOUS`, bấm vào icon mũi tên xuống `[\v/]` trên thẻ giải đấu Đức. Thẻ trượt mở rộng tại chỗ thành `[^]`, hiển thị ngay danh sách: `Players: L.Q.Liem, Magnus Carlsen, Caruana...` mà không cần tải lại trang.
  - **Lời thoại:** Phú vui mừng: _"Bấm mở thẻ tại chỗ là thấy ngay danh sách kỳ thủ, tiện quá!"_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`schedule_1_default_collapsed.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/schedule_1_default_collapsed.JPG) và [`schedule_1_default_expanded.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/schedule_1_default_expanded.JPG).

- **🔹 Nhánh 4B (Variant 2 - Date Dropdown Filter + Dedicated Detail Page):**
  - **Hình ảnh vẽ:** Phú bấm chọn bộ lọc Dropdown `[August v]` và `[2026 v]`, sau đó bấm nút `[Detail ->]` trên thẻ trận đấu. Hệ thống chuyển sang **Trang chi tiết riêng** có thông tin cặp đấu `L.Q.Liem vs Magnus Carlsen` và hình bàn cờ phân tích thế trận.
  - **Lời thoại:** Phú trầm trồ: _"Có cả trang chi tiết cặp đấu và bàn cờ phân tích chuyên sâu luôn này!"_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`schedule_2_dropdowns.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/schedule_2_dropdowns.JPG), [`match.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/match.JPG).

- **🔹 Nhánh 4C (Variant 3 - Vertical Infinite Timeline):**
  - **Hình ảnh vẽ:** Màn hình có trục thời gian dọc với vạch đỏ `Today` ở giữa. Phú dùng ngón tay vuốt ngược màn hình lên trên (`Scroll UP hướng về Past`). Trục thời gian trượt mượt mà hiển thị các giải đấu quá khứ theo thứ tự năm 2023, 2020.
  - **Lời thoại:** Phú thích thú: _"Vuốt dòng thời gian lên quá khứ như lướt story, siêu trực quan!"_
  - **Liên kết Paper Prototype:** Minh họa ảnh [`schedule_3_default.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/schedule_3_default.JPG), [`schedule_3_scroll_up.JPG`](file:///d:/LEARNING/CNTT_CLC(2023-2027)/NamBa/HK3/Thiết kế giao diện/PA3/TKGD_PA3/paper_prototype/schedule_3_scroll_up.JPG).

---

#### 🖼️ Khung 5: Kết quả & Sự thỏa mãn (Outcome & Validation)

- **Hình ảnh vẽ:** Phú quay màn hình điện thoại sang cho bạn xem. Cả hai bạn cùng tươi cười gật gù tâm đắc.
- **Bóng thoại:** Bạn của Phú thốt lên: _"Ồ chuẩn rồi, có đủ cả Liêm và Carlsen này! Thông tin rõ ràng thật đấy!"_
- **Chú thích (Caption):** Người dùng tra cứu thành công thông tin mong muốn nhanh chóng, trải nghiệm người dùng nâng cao vượt trội.

---

## IV. BẢNG TỔNG KẾT ÁNH XẠ GIỮA STORYBOARD VÀ PAPER PROTOTYPE

| Kịch bản                      | Khung Storyboard | Vấn đề UX (Problem)        | Giải pháp UI Paper Prototype                                | Tệp ảnh minh họa                                                      |
| :---------------------------- | :--------------- | :------------------------- | :---------------------------------------------------------- | :-------------------------------------------------------------------- |
| **Storyboard 1** (Navigation) | Khung 4A         | Menu trên cùng khó với     | **Fixed Bottom Navigation Bar** (4-5 tabs ở đáy)            | `nav_1.JPG`                                                           |
|                               | Khung 4B         | Vướng tầm nhìn nội dung    | **Floating Action Button** (Nút tròn nổi góc phải)          | `nav_2.JPG`                                                           |
|                               | Khung 4C         | Menu cũ nhưng đặt sai chỗ  | **Bottom Hamburger Menu** (Nút 3 gạch dời xuống đáy)        | `nav_3_menu.JPG`                                                      |
| **Storyboard 2** (Schedule)   | Khung 4A         | Thiếu danh sách kỳ thủ     | **Accordion / Collapsible Cards** (Mở rộng thẻ tại chỗ)     | `schedule_1_default_collapsed.JPG`, `schedule_1_default_expanded.JPG` |
|                               | Khung 4B         | Cần xem chuyên sâu cặp đấu | **Date Filter + Dedicated Detail Page** (Có bàn cờ)         | `schedule_2_dropdowns.JPG`, `match.JPG`                               |
|                               | Khung 4C         | Khó hình dung lịch sử giải | **Vertical Infinite Timeline** (Vuốt 2 chiều Past / Future) | `schedule_3_default.JPG`, `schedule_3_scroll_up.JPG`                  |

---

## V. HƯỚNG DẪN DÀNH CHO THÀNH VIÊN VẼ TAY & LÀM VIDEO

1. **Chuẩn bị:** 2 tờ giấy A4 trắng không dòng kẻ, chia mỗi tờ thành 6 ô chữ nhật bằng nhau (mỗi ô kích thước khoảng 9cm x 6cm).
2. **Dụng cụ:** Bút lông kim đen (để vẽ nét chính) và bút dạ màu (xanh dương cho UI, đỏ/vàng cho điểm nhấn/icon).
3. **Thực hiện vẽ:** Vẽ theo đúng mô tả từng khung ở Mục II và Mục III bên trên.
4. **Quay video & Chèn báo cáo:**
   - Chụp ảnh sắc nét từng khung Storyboard để chèn vào đầu phần giải thích phương án trong file PDF `GroupID-PA3-PaperProtype.pdf`.
   - Trong video YouTube demo prototype, dành 10-15 giây đầu tiên lia camera vào tranh Storyboard và thuyết minh bối cảnh trước khi chuyển sang thao tác tráo giấy Paper Prototype.
