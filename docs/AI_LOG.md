# NHẬT KÝ KIỂM TRA SAU KHI SỬA

Ngày kiểm tra: 30/10/2026
Phạm vi: Trang kết quả và đường dẫn CSS

| Mã   | Trường hợp kiểm tra                      | Kết quả                                   |
| ---- | ---------------------------------------- | ----------------------------------------- |
| TC01 | Kiểm tra liên kết CSS trong ket-qua.html | ĐẠT - css/style.css                       |
| TC02 | Kiểm tra CSS trên GitHub Pages           | ĐẠT - css/style.css trả về mã 200         |
| TC03 | Kiểm tra trang ket-qua.html trên GitHub  | ĐẠT - trang trả về mã 200                 |
| TC04 | Kiểm tra trang chính có trạng thái 304   | ĐẠT - phản hồi bộ nhớ đệm, không phải lỗi |

Kết luận:

- Đã sửa đường dẫn CSS của trang kết quả từ style.css
  thành css/style.css, phù hợp với vị trí tệp css/style.css.
- Đường dẫn style.css ở thư mục gốc không tồn tại (404);
  không sử dụng đường dẫn này.
- Trang chính trả về mã 304 khi tải lại; đây là hành vi bộ nhớ đệm bình thường.
- Đã kiểm tra mã HTML và mã trạng thái HTTP; chưa kiểm tra hiển thị
  bằng thao tác trực tiếp trên trình duyệt.

# NHẬT KÝ KIỂM TRA VÀ SỬ DỤNG AI

## 1. Nhật ký kiểm tra website

**Ngày kiểm tra:** 30/10/2026

**Phạm vi:** Trang kết quả và đường dẫn CSS.

| Mã   | Trường hợp kiểm tra                         | Kết quả                                   |
| ---- | ------------------------------------------- | ----------------------------------------- |
| TC01 | Kiểm tra liên kết CSS trong ket-qua.html    | ĐẠT – css/style.css                       |
| TC02 | Kiểm tra CSS trên GitHub Pages              | ĐẠT – css/style.css trả về mã HTTP 200    |
| TC03 | Kiểm tra trang ket-qua.html trên GitHub     | ĐẠT – trang trả về mã HTTP 200            |
| TC04 | Kiểm tra trang chính có trạng thái HTTP 304 | ĐẠT – phản hồi bộ nhớ đệm, không phải lỗi |

### Kết luận

- Đã sửa đường dẫn CSS của trang kết quả từ style.css thành css/style.css, phù hợp với vị trí tệp css/style.css.
- Đường dẫn style.css ở thư mục gốc không tồn tại (404), không sử dụng đường dẫn này.
- Trang chính trả về mã 304 khi tải lại; đây là hành vi bộ nhớ đệm bình thường.
- Đã kiểm tra mã HTML và mã trạng thái HTTP; chưa kiểm tra hiển thị bằng thao tác trực tiếp trên trình duyệt.

## 2. Nhật ký sử dụng AI trong Lab 8

| Ngày       | Dùng AI làm gì                                                                                                   | Em sửa lại gì                                                                                                              |
| ---------- | ---------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| 05/11/2026 | Hỗ trợ đọc hướng dẫn Lab 8, kiểm tra cấu trúc repository và chuẩn bị nội dung README, CHANGELOG, bảng minh chứng | Đối chiếu nội dung với mã nguồn và cấu trúc thực tế của Portfolio; kiểm tra lại các thông tin trước khi đưa vào repository |

### Cam kết

AI được sử dụng như công cụ hỗ trợ đọc tài liệu, rà soát cấu trúc và chuẩn bị nội dung. Người thực hiện có trách nhiệm kiểm tra, chỉnh sửa và xác nhận tính chính xác của các thông tin trước khi nộp bài.
