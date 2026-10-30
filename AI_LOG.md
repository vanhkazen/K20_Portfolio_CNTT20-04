NHẬT KÝ KIỂM TRA SAU KHI SỬA
============================

Ngày kiểm tra: 30/10/2026
Phạm vi: Trang kết quả và đường dẫn CSS

Mã  | Trường hợp kiểm tra                     | Kết quả
----|-----------------------------------------|--------------------------------------------
TC01 | Kiểm tra liên kết CSS trong ket-qua.html | ĐẠT - css/style.css
TC02 | Kiểm tra CSS trên GitHub Pages           | ĐẠT - css/style.css trả về mã 200
TC03 | Kiểm tra trang ket-qua.html trên GitHub  | ĐẠT - trang trả về mã 200
TC04 | Kiểm tra trang chính có trạng thái 304   | ĐẠT - phản hồi bộ nhớ đệm, không phải lỗi

Kết luận:
- Đã sửa đường dẫn CSS của trang kết quả từ style.css
  thành css/style.css, phù hợp với vị trí tệp css/style.css.
- Đường dẫn style.css ở thư mục gốc không tồn tại (404);
  không sử dụng đường dẫn này.
- Trang chính trả về mã 304 khi tải lại; đây là hành vi bộ nhớ đệm bình thường.
- Đã kiểm tra mã HTML và mã trạng thái HTTP; chưa kiểm tra hiển thị
  bằng thao tác trực tiếp trên trình duyệt.
