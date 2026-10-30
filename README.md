# Portfolio CV - Trần Việt Anh

Website portfolio cá nhân được xây dựng trong quá trình học môn **Thiết kế Web và Triển khai hệ thống phần mềm**. Dự án giới thiệu thông tin, kỹ năng, sản phẩm học tập và thông tin liên hệ của sinh viên Công nghệ Thông tin.

## Nội dung

- Giới thiệu cá nhân và định hướng học tập.
- Danh sách kỹ năng đang học và sử dụng.
- Một số dự án, bài tập thực hành.
- Bảng thông tin học tập.
- Thông tin liên hệ và form gửi lời nhắn.
- Giao diện tương thích với các kích thước màn hình khác nhau.

## Công nghệ

- HTML5
- CSS3
- Google Fonts (Inter)

## Chạy dự án

Đây là website tĩnh, không cần cài đặt thư viện hay chạy máy chủ.

1. Tải hoặc clone repository về máy.
2. Mở `index.html` bằng trình duyệt.

Trong Visual Studio Code, có thể mở thư mục dự án và dùng tiện ích **Live Server** để xem trang trong quá trình chỉnh sửa. Trang kết quả của form là `ket-qua.html`.

## Cấu trúc thư mục

```text
.
├── index.html       # Trang portfolio chính
├── ket-qua.html     # Trang kết quả sau khi gửi form
├── css/
│   └── style.css    # Kiểu dáng và bố cục
└── assets/          # Ảnh đại diện và hình minh họa dự án
```

## Lưu ý về form liên hệ

Form hiện dùng phương thức `GET` để thực hành kiểm tra dữ liệu HTML5 và chuyển đến trang kết quả. Form **không gửi email, không lưu dữ liệu lên máy chủ**; các giá trị đã nhập có thể xuất hiện trên thanh địa chỉ. Không nhập thông tin nhạy cảm vào form.
