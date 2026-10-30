# Portfolio CV - Trần Việt Anh

Website portfolio cá nhân của **Trần Việt Anh**, sinh viên ngành Công nghệ Thông tin, lớp CNTT 20-04. Sản phẩm giới thiệu thông tin cá nhân, kỹ năng đang học, các bài tập/dự án, quá trình học tập và thông tin liên hệ. Website gồm trang portfolio chính và trang kết quả thực hành form liên hệ; giao diện được xây dựng bằng HTML và CSS, có bố cục responsive.

## Hồ sơ và minh chứng

- **Tác giả:** [Trần Việt Anh](https://github.com/vanhkazen)
- **Repository:** [vanhkazen/K20_Portfolio_CNTT20-04](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04)
- **Website GitHub Pages:** [Mở portfolio](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/)
- **Trang kết quả form:** [Mở trang kết quả](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/ket-qua.html)
- **Mã nguồn minh chứng:** [Trang chính](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/blob/main/index.html), [trang kết quả](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/blob/main/ket-qua.html), [CSS](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/blob/main/css/style.css)

## Nội dung và công nghệ

- Giới thiệu cá nhân và định hướng học tập.
- Kỹ năng C++ cơ bản, HTML5, CSS3 và các dự án/bài tập học tập.
- Bảng thông tin học tập và thông tin liên hệ.
- Form thực hành kiểm tra dữ liệu HTML5.
- HTML5, CSS3 và Google Fonts (Inter); không dùng framework hay thư viện JavaScript.

## Nguồn xuất bản

Website được xuất bản bằng **GitHub Pages** từ repository ở trên. Mã nguồn website là các tệp tĩnh trong repository; trang Pages hiện được truy cập tại `https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/`.

## Chạy local

Website không cần cài package hay biên dịch. Có thể clone repository và mở trực tiếp `index.html` bằng trình duyệt:

```bash
git clone https://github.com/vanhkazen/K20_Portfolio_CNTT20-04.git
cd K20_Portfolio_CNTT20-04
```

Hoặc chạy một máy chủ tĩnh để kiểm tra các đường dẫn như khi xuất bản:

```bash
python -m http.server 8000
```

Sau đó mở `http://localhost:8000/`. Dừng máy chủ bằng `Ctrl+C`. Nếu dùng VS Code, có thể mở thư mục dự án và dùng tiện ích Live Server thay cho lệnh trên.

## Cấu trúc thư mục

```text
.
├── index.html                                      # Portfolio chính
├── ket-qua.html                                    # Trang kết quả form liên hệ
├── css/
│   └── style.css                                   # Giao diện và responsive
├── assets/
│   ├── 791975572_1060704449904978_7434436045093909714_n.jpg  # Ảnh đại diện
│   ├── du-an-1.svg                                 # Minh họa dự án C++
│   ├── du-an-2.svg                                 # Minh họa portfolio
│   └── du-an-3.svg                                 # Minh họa website thực hành
├── README.md                                       # Hướng dẫn dự án
├── RELEASE_NOTES.md                                # Ghi chú phát hành
└── AI_LOG.md                                       # Nhật ký kiểm tra
```

## Cách kiểm tra trang và chức năng chính

1. Mở [website đã xuất bản](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/) hoặc `http://localhost:8000/`.
2. Dùng menu **Giới thiệu**, **Kỹ năng**, **Dự án**, **Học tập**, **Liên hệ** để kiểm tra các phần trên trang chính.
3. Kiểm tra ảnh đại diện và ba hình minh họa dự án hiển thị; thay đổi chiều rộng cửa sổ hoặc dùng chế độ thiết bị di động để kiểm tra bố cục responsive.
4. Trong phần **Liên hệ**, thử gửi form để kiểm tra các trường bắt buộc, định dạng email, độ dài họ tên và lời nhắn. Khi hợp lệ, form chuyển đến `ket-qua.html`; dùng liên kết **Quay lại liên hệ** để trở về.
5. Có thể mở trực tiếp [trang kết quả](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/ket-qua.html) để xác nhận trang tải được và menu điều hướng về đúng các mục của trang chính.
6. Kiểm tra các liên kết hồ sơ GitHub, repository và email ở phần liên hệ.

Nhật ký kiểm tra trong thư mục dự án (`AI_LOG.md`) ghi nhận kiểm tra đường dẫn CSS và phản hồi của các trang trên GitHub Pages; hiển thị trực tiếp trên nhiều kích thước màn hình cần được xác nhận bằng trình duyệt theo checklist trên.

## Lưu ý về form

Form dùng phương thức `GET` để thực hành kiểm tra dữ liệu HTML5 và chuyển đến trang kết quả. Form **không gửi email và không lưu dữ liệu lên máy chủ**. Giá trị nhập có thể xuất hiện trên URL, vì vậy chỉ dùng dữ liệu thử, không nhập thông tin nhạy cảm.
