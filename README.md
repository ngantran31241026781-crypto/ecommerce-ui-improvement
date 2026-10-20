# E-Commerce UI Improvement - Sách Chương Mới

## 1. Giới thiệu
Dự án thực hiện cải tiến giao diện hiển thị thẻ sản phẩm (Product Card) cho website bán sách cũ "Sách Chương Mới". Bài tập giúp tối ưu trải nghiệm người dùng, giúp khách hàng dễ dàng nhận biết thông tin độ mới của sách, giá gốc, giá bán và thao tác thêm vào giỏ hàng rõ ràng hơn trên cả máy tính và điện thoại.

## 2. Website tham khảo
- Tên website: Sách Chương Mới
- URL: https://www.sachchuongmoi.com/
- Khu vực đã khảo sát: Trang chủ, Danh mục sản phẩm, Chi tiết sản phẩm, Tìm kiếm, Giỏ hàng.

## 3. Chức năng
- Hiển thị danh sách thẻ sản phẩm dạng lưới (Grid).
- Hiển thị nhãn tình trạng sách (Mới 80%, Mới 85%, Bookcare Free, Chữ ký tác giả).
- Hiển thị tên sách, tác giả, giá gốc và giá bán ưu đãi.
- Nút "Thêm vào giỏ" rõ ràng kèm biểu tượng.
- Bố cục co giãn linh hoạt (Responsive) tự động điều chỉnh 4 cột trên máy tính và 2 cột trên điện thoại.

## 4. Công nghệ sử dụng
- HTML5
- CSS3 (CSS Grid, Flexbox, Media Queries)

## 5. Cách chạy dự án
- Tải mã nguồn về máy tính.
- Nhấp đôi chuột (double-click) vào file `index.html` để mở trực tiếp trên trình duyệt web (Chrome/Edge/Firefox).

## 6. Cải tiến đã thực hiện
- **Vấn đề ban đầu:** Thẻ sản phẩm cũ chỉ có biểu tượng giỏ hàng nhỏ ở góc, chưa hiển thị nổi bật trạng thái độ mới của sách cũ ngay ở danh sách.
- **Thay đổi đã thực hiện:** 
  - Thiết kế nhãn dán (Badge) đè lên góc ảnh sách để hiển thị ngay độ mới (%) và ưu đãi.
  - Thiết kế lại nút "Thêm vào giỏ" dạng hình chữ nhật màu xanh nổi bật đầy đủ chữ và icon.
  - Sử dụng Flexbox để căn thẳng hàng nút bấm ở đáy thẻ sản phẩm dù tên sách dài ngắn khác nhau.

## 7. Hỗ trợ từ AI
- Sử dụng AI để gợi ý cấu trúc phân tích UX/UI cho 5 khu vực website và tham khảo bố cục HTML/CSS dạng Responsive Grid.
- Bản thân sinh viên đã trực tiếp đối chiếu, loại bỏ thông tin AI phân tích sai, kiểm tra hiển thị trên Chrome DevTools và tự chỉnh sửa CSS để căn thẳng hàng các thành phần.