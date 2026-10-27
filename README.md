# Portfolio CV - Hoàng Văn Việt

## 1. Tên dự án

**Portfolio CV cá nhân của Hoàng Văn Việt**

## 2. Mô tả

Đây là website portfolio/CV tĩnh giới thiệu thông tin cá nhân, kỹ năng, một số dự án tiêu biểu và cách liên hệ với Hoàng Văn Việt. Giao diện được thiết kế để hiển thị trên máy tính, máy tính bảng và điện thoại.

Website hiện chỉ chạy ở phía trình duyệt, không có máy chủ ứng dụng, cơ sở dữ liệu hay bước biên dịch. Biểu mẫu “Sign in” là giao diện minh họa; chức năng đăng nhập và đăng ký chưa được kết nối. Các liên kết GitHub và LinkedIn trong trang cũng cần được cập nhật nếu muốn trỏ đến hồ sơ thật.

## 3. Chức năng chính

- Giới thiệu cá nhân và định hướng học tập/nghề nghiệp.
- Trình bày các kỹ năng như HTML5, CSS3, JavaScript, responsive design, Git/GitHub và Figma.
- Hiển thị các thẻ dự án kèm hình ảnh, mô tả và liên kết tham khảo.
- Điều hướng nhanh đến phần Giới thiệu, Kỹ năng, Dự án và Liên hệ.
- Cung cấp email liên hệ và giao diện đăng nhập minh họa.
- Tương thích với các kích thước màn hình phổ biến.

## 4. Công nghệ sử dụng

- **HTML5:** cấu trúc và nội dung trang.
- **CSS3:** giao diện, bố cục Flexbox/Grid và responsive design.
- **JavaScript:** hiện chưa sử dụng.
- **Tài nguyên tĩnh:** hình ảnh nằm trong thư mục `assets/img/`; stylesheet nằm tại `assets/css/styles.css`.

## 5. Yêu cầu môi trường

- Windows, Linux hoặc macOS.
- Trình duyệt hiện đại như Google Chrome, Microsoft Edge, Mozilla Firefox hoặc Safari.
- Không cần cài Node.js, cơ sở dữ liệu hay thư viện bổ sung.
- Để mở trực tiếp, chỉ cần trình duyệt. Để chạy qua máy chủ web cục bộ, có thể cài **Python 3** hoặc dùng tiện ích **Live Server** trong Visual Studio Code.

## 6. Cài đặt

### Cách 1: Tải mã nguồn

Tải hoặc giải nén toàn bộ dự án vào một thư mục trên máy. Đảm bảo giữ nguyên cấu trúc thư mục, đặc biệt là `index.html` và thư mục `assets/`.

### Cách 2: Sao chép bằng Git (tùy chọn)

Nếu dự án đã được đưa lên một kho Git, mở Terminal/PowerShell và chạy lệnh sau, thay URL bằng địa chỉ kho dự án:

```bash
git clone <URL-kho-du-an>
```

Sau đó mở thư mục dự án vừa tải về.

## 7. Cấu hình

Không cần cấu hình môi trường để xem website. Để chỉnh sửa nội dung:

1. Mở `index.html` bằng trình soạn thảo mã nguồn.
2. Sửa nội dung, thông tin liên hệ hoặc liên kết trong HTML.
3. Sửa màu sắc, bố cục và kiểu chữ trong `assets/css/styles.css`.
4. Thay ảnh trong `assets/img/` và cập nhật đường dẫn tương ứng trong HTML nếu đổi tên hoặc vị trí ảnh.

Email hiện được hiển thị trên trang là `van835592@gmail.com`. Hãy kiểm tra và thay thông tin này cùng các liên kết hồ sơ trước khi xuất bản website.

## 8. Chạy thử

### Mở trực tiếp

Mở file `index.html` bằng trình duyệt. Cách này phù hợp để xem nhanh giao diện; một số tính năng trên trình duyệt có thể hoạt động ổn định hơn khi dùng máy chủ cục bộ.

### Chạy bằng máy chủ Python

Mở cửa sổ dòng lệnh tại **thư mục gốc của dự án** — thư mục chứa `index.html` — rồi chạy:

```bash
python -m http.server 8000
```

Nếu lệnh `python` không khả dụng, thử `python3`; trên Windows có thể thử `py -m http.server 8000`. Mở trình duyệt tại:

```text
http://localhost:8000
```

Nhấn `Ctrl+C` trong cửa sổ dòng lệnh để dừng máy chủ.

### Windows

1. Mở thư mục dự án trong File Explorer.
2. Mở PowerShell tại thư mục chứa `index.html` (nhấp chuột phải trong thư mục và chọn **Open in Terminal**, hoặc mở Terminal rồi dùng `cd` để chuyển đến thư mục dự án).
3. Chạy:

   ```powershell
   py -m http.server 8000
   ```

4. Truy cập `http://localhost:8000` bằng trình duyệt. Nếu không có lệnh `py`, thử `python -m http.server 8000`.

### Linux

1. Mở Terminal và chuyển đến thư mục dự án:

   ```bash
   cd "/duong-dan/toi/thu-muc-du-an"
   ```

2. Chạy máy chủ:

   ```bash
   python3 -m http.server 8000
   ```

3. Truy cập `http://localhost:8000` bằng trình duyệt.

### macOS

1. Mở Terminal và chuyển đến thư mục dự án:

   ```bash
   cd "/duong-dan/toi/thu-muc-du-an"
   ```

2. Chạy máy chủ:

   ```bash
   python3 -m http.server 8000
   ```

3. Truy cập `http://localhost:8000` bằng Safari hoặc trình duyệt khác.

> Nếu cổng `8000` đang được sử dụng, thay `8000` trong lệnh và địa chỉ truy cập bằng một cổng khác, ví dụ `8080`.

### Chạy bằng Visual Studio Code (tùy chọn)

1. Mở thư mục dự án trong Visual Studio Code.
2. Cài tiện ích **Live Server** nếu máy chưa có.
3. Nhấp chuột phải vào `index.html`, chọn **Open with Live Server**.
4. Trình duyệt sẽ mở trang; khi lưu thay đổi, Live Server thường tự tải lại trang.

## 9. Thông tin liên hệ

- **Tác giả:** Hoàng Văn Việt
- **Email:** [van835592@gmail.com](mailto:van835592@gmail.com)
- **GitHub:** `github.com/hoangviet2k8` (cập nhật liên kết trong `index.html` nếu cần)
- **LinkedIn:** `linkedin.com/in/hoangvanviet` (cập nhật liên kết trong `index.html` nếu cần)