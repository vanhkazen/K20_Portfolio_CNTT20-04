# Portfolio CV – Trần Việt Anh

## 1. Sản phẩm này là gì?

Portfolio CV cá nhân của Trần Việt Anh, sinh viên ngành Công nghệ Thông tin, lớp CNTT 20-04. Website giới thiệu thông tin cá nhân, kỹ năng lập trình đang học, các dự án thực hành, quá trình học tập và thông tin liên hệ. Sản phẩm được xây dựng bằng HTML5 và CSS3.

## 2. Demo

- **Website chính:** https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/
- **Trang kết quả form:** https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/ket-qua.html
- **Repository:** https://github.com/vanhkazen/K20_Portfolio_CNTT20-04

## 3. Tính năng

- Giới thiệu thông tin cá nhân và định hướng học tập.
- Trình bày các kỹ năng C++, HTML5, CSS3 và sử dụng Visual Studio Code.
- Hiển thị ba dự án học tập với hình ảnh minh họa.
- Bảng thông tin học tập theo học kỳ.
- Cung cấp email và liên kết GitHub.
- Form liên hệ có kiểm tra dữ liệu bằng HTML5.
- Bố cục responsive hỗ trợ các kích thước màn hình khác nhau.

## 4. Công nghệ sử dụng

- HTML5: xây dựng cấu trúc và nội dung website.
- CSS3: thiết kế giao diện và bố cục responsive.
- Google Fonts – Inter: hiển thị kiểu chữ.
- Git và GitHub: quản lý mã nguồn.
- GitHub Pages: xuất bản website.

Website không sử dụng framework hoặc thư viện JavaScript.

## 5. Cách mở website

### Truy cập bản trực tuyến

1. Mở trình duyệt Google Chrome hoặc Microsoft Edge.
2. Nhập địa chỉ https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/ vào thanh địa chỉ.
3. Nhấn Enter để truy cập website.
4. Sử dụng menu Giới thiệu, Kỹ năng, Dự án, Học tập và Liên hệ để xem nội dung.
5. Trong phần Liên hệ, có thể nhập dữ liệu thử vào biểu mẫu và nhấn Gửi lời nhắn để mở trang kết quả.

### Chạy trên máy tính cá nhân

1. Mở repository tại https://github.com/vanhkazen/K20_Portfolio_CNTT20-04.
2. Nhấn nút Code và chọn Download ZIP hoặc sử dụng Git để clone repository.
3. Giải nén thư mục dự án nếu tải bằng ZIP.
4. Mở thư mục dự án bằng Visual Studio Code.
5. Mở tệp index.html bằng trình duyệt hoặc chạy máy chủ tĩnh bằng Terminal:

```bash
python -m http.server 8000
```

6. Mở trình duyệt và truy cập http://localhost:8000/.

7. Nhấn Ctrl+C trong Terminal để dừng máy chủ sau khi kiểm tra.

## 6. Cấu trúc thư mục

```text
K20_Portfolio_CNTT20-04/
├── assets/
│   ├── ảnh đại diện
│   ├── du-an-1.svg
│   ├── du-an-2.svg
│   └── du-an-3.svg
├── css/
│   └── style.css
├── docs/
│   ├── AI_LOG.md
│   ├── evidence-index.md
│   └── evidence/
├── index.html
├── ket-qua.html
├── README.md
├── CHANGELOG.md
└── RELEASE_NOTES.md
```

## 7. Kết quả kiểm tra

Một số nội dung đã được kiểm tra và ghi nhận trong nhật ký:

- Đường dẫn CSS trong trang ket-qua.html.
- Tệp CSS trên GitHub Pages trả về mã HTTP 200.
- Trang ket-qua.html trên GitHub Pages trả về mã HTTP 200.
- Trang chính trả về mã HTTP 304 khi tải lại, là phản hồi bộ nhớ đệm bình thường.

Bảng kiểm thử và minh chứng chi tiết được lưu tại [docs/evidence-index.md](docs/evidence-index.md).

## 8. Hạn chế và nội dung chưa kiểm tra

- Ba dự án hiện sử dụng hình ảnh minh họa; các liên kết GitHub của từng dự án vẫn cần được cập nhật.
- Biểu mẫu liên hệ chỉ phục vụ thực hành kiểm tra dữ liệu HTML5, chưa gửi email và không lưu dữ liệu lên máy chủ.
- Chưa xác nhận đầy đủ giao diện trên các thiết bị di động thực tế.
- Các nội dung kiểm thử bổ sung sẽ được cập nhật trong bảng minh chứng khi hoàn thành.

## 9. Khai báo sử dụng AI

Nhật ký sử dụng AI trong quá trình thực hiện và hoàn thiện Lab 8 được lưu tại [docs/AI_LOG.md](docs/AI_LOG.md).
