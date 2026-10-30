# Ghi chú phát hành — Portfolio CV v7

## Thông tin phiên bản

- **Tên sản phẩm:** Portfolio CV - Trần Việt Anh
- **Mã phiên bản:** v7
- **Ngày cập nhật:** 30/10/2026
- **Tác giả:** [Trần Việt Anh](https://github.com/vanhkazen)
- **Repository:** [vanhkazen/K20_Portfolio_CNTT20-04](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04)
- **Bản mã được bàn giao:** [Commit `d422a087a93154b1897e5cb476aa2eed2281a882`](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/commit/d422a087a93154b1897e5cb476aa2eed2281a882)
- **Website:** [GitHub Pages](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/)

Liên kết commit ở trên là snapshot mã nguồn trên nhánh `main` tại thời điểm ghi chú này được lập. Các chỉnh sửa tài liệu chưa commit trong thư mục làm việc không thuộc snapshot đó.

## Thay đổi chính

- Hoàn thiện portfolio tĩnh bằng HTML5 và CSS3, có bố cục responsive.
- Trình bày phần giới thiệu, kỹ năng, dự án học tập, thông tin học tập và liên hệ.
- Bổ sung trang `ket-qua.html` làm đích chuyển đến của form liên hệ.
- Form kiểm tra dữ liệu bằng các ràng buộc HTML5, không cần backend.

## Lỗi đã sửa

- Trang kết quả dùng đúng đường dẫn stylesheet `css/style.css` thay vì đường dẫn ở thư mục gốc không tồn tại. Nhật ký kiểm tra ghi nhận stylesheet và trang kết quả truy cập được trên GitHub Pages; trang chính trả mã HTTP 304 khi tải lại do bộ nhớ đệm, không phải lỗi.

## Commit liên quan

- [`d422a08` — Fix and update files](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/commit/d422a087a93154b1897e5cb476aa2eed2281a882): commit mới nhất tại thời điểm lập ghi chú; cập nhật nhật ký kiểm thử.
- [`96ec8c9` — Fix and update files](https://github.com/vanhkazen/K20_Portfolio_CNTT20-04/commit/96ec8c91f83b331fcc08abaf6afa2f87f9e5da81): cập nhật định dạng trang kết quả và nhật ký liên quan.

## Hạn chế còn lại

- Form dùng `GET`, chỉ chuyển sang trang kết quả; không gửi email và không lưu dữ liệu. Giá trị nhập có thể xuất hiện trên URL, vì vậy không nhập thông tin nhạy cảm.
- Liên kết GitHub của các thẻ dự án trong trang portfolio vẫn là nội dung chờ cập nhật, chưa dẫn tới repository dự án cụ thể.
- Nhật ký hiện có xác nhận một số đường dẫn và mã trạng thái HTTP; chưa có kiểm tra giao diện trực tiếp trên nhiều trình duyệt hoặc kích thước màn hình.
- Google Fonts cần kết nối Internet để tải phông Inter; trang vẫn có phông dự phòng nếu không tải được.

## Tiếp tục kiểm tra và bàn giao

1. Tải đúng snapshot mã nguồn bằng cách clone repository rồi checkout commit v7:

   ```bash
   git clone https://github.com/vanhkazen/K20_Portfolio_CNTT20-04.git
   cd K20_Portfolio_CNTT20-04
   git checkout d422a087a93154b1897e5cb476aa2eed2281a882
   ```

2. Chạy website tĩnh cục bộ:

   ```bash
   python -m http.server 8000
   ```

   Mở `http://localhost:8000/`; dừng máy chủ bằng `Ctrl+C`.

3. Kiểm tra menu và các phần trên trang chính, ảnh và hình dự án, bố cục ở màn hình rộng/hẹp, liên kết hồ sơ; thử form với dữ liệu thiếu/sai và dữ liệu hợp lệ. Xác nhận dữ liệu hợp lệ chuyển tới `ket-qua.html`, rồi dùng nút quay lại.
4. Mở trực tiếp `http://localhost:8000/ket-qua.html` và xác nhận CSS tải đúng. Đối chiếu kết quả xuất bản tại [GitHub Pages](https://vanhkazen.github.io/K20_Portfolio_CNTT20-04/) và nhật ký trong [`AI_LOG.md`](./AI_LOG.md).
5. Khi bàn giao tài liệu cùng mã nguồn, commit `RELEASE_NOTES.md` và các tài liệu liên quan trên nhánh cần nộp. Giữ nguyên liên kết commit v7 để người nhận phân biệt snapshot mã nguồn được mô tả với các cập nhật sau đó.
