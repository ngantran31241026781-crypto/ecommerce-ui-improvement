# AI Usage Log

## 1. Công cụ AI
- Tên công cụ: ChatGPT / Claude / Gemini

## 2. Mục đích sử dụng
- Phân tích trải nghiệm người dùng (UX/UI) 5 khu vực trên website bán sách cũ `sachchuongmoi.com`.
- Gợi ý cấu trúc HTML5 và kĩ thuật tổ chức CSS3 Responsive (Grid/Flexbox) cho thẻ sản phẩm.

## 3. Prompt đã sử dụng
- **Prompt 1:** *"Bạn là chuyên gia phân tích nghiệp vụ và thiết kế trải nghiệm người dùng cho website thương mại điện tử. Tôi đang khảo sát website: Sách Chương Mới (https://www.sachchuongmoi.com/). Hãy giúp tôi lập bảng phân tích các khu vực: 1. Trang chủ, 2. Danh mục sản phẩm, 3. Chi tiết sản phẩm, 4. Tìm kiếm, 5. Giỏ hàng. Với mỗi khu vực, hãy nêu: Mục đích của chức năng, Thành phần giao diện cần có, Điểm thuận tiện đối với khách hàng, Một vấn đề có thể phát sinh, Một đề xuất cải tiến. Không khẳng định những tính năng chưa được kiểm chứng. Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI."*
- **Prompt 2:** *"Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Tôi muốn cải tiến khu vực: Thẻ sản phẩm và danh sách sản phẩm. Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam. Hãy đề xuất: 1. Bố cục giao diện, 2. Các thành phần HTML cần sử dụng, 3. Cách tổ chức CSS, 4. Cách hiển thị trên máy tính và điện thoại, 5. Những điểm cần kiểm tra về khả năng sử dụng."*

## 4. Kết quả AI đề xuất
- AI đề xuất bảng phân tích chi tiết cho 5 khu vực và gợi ý cấu trúc mã HTML5 kết hợp CSS Grid để tạo danh sách sản phẩm hiển thị đa thiết bị.

## 5. Kiểm tra và điều chỉnh
- **Loại bỏ nhận xét sai của AI:** AI nhận xét website thiếu thông tin độ mới của sách cũ và không chọn được dịch vụ bọc sách, tuy nhiên thực tế kiểm tra website đã có đủ 2 tính năng này.
- **Tự điều chỉnh mã nguồn:** Phát hiện lỗi nút bấm bị lệch hàng do độ dài tên sách không đồng đều trên màn hình điện thoại, sinh viên đã tự bổ sung thuộc tính Flexbox (`flex-grow: 1; margin-top: auto;`) vào file `css/style.css` để căn thẳng hàng nút bấm ở sát đáy thẻ.

## 6. Phần tôi hiểu và có thể giải thích
- Hiểu cấu trúc semantic HTML5 (`header`, `main`, `footer`, `article`, `section`).
- Hiểu cách hoạt động của CSS Grid (`grid-template-columns`) để làm bố cục cột và Media Queries (`@media`) để tự động thu gọn giao diện trên điện thoại.
- Hiểu cơ chế căn chỉnh vị trí tuyệt đối/tương đối (`position: absolute/relative`) để làm các nhãn Badge đè lên ảnh sản phẩm.