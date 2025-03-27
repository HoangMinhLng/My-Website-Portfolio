<!-- Cách Chỉnh Sửa và Triển Khai Website Portfolio -->
📄 README.md – Tài liệu hướng dẫn về dự án

**Cấu Trúc Thư Mục**

📂 data
├── personal-data.js – Dữ liệu thông tin cá nhân
├── projects-data.js – Dữ liệu về các dự án
├── services-data.js – Dữ liệu về các dịch vụ

📂 images-and-icons
├── icons – Tệp biểu tượng
├── images – Hình ảnh chung

📂 script
├── about.js – Script cho phần giới thiệu
├── main.js – Tệp script chính
├── projects.js – Script cho phần dự án
├── render-contents.js – Render nội dung động
├── top-nav.js – Script cho thanh điều hướng

📂 style
├── sections-style/ – CSS cho từng phần của website
│ ├── about-section.css – CSS cho phần giới thiệu
│ ├── contact-section.css – CSS cho phần liên hệ
│ ├── projects-section.css – CSS cho phần dự án
│ ├── services-section.css – CSS cho phần dịch vụ
├── animation.css – CSS cho hiệu ứng
├── footer.css – CSS cho phần chân trang
├── global.css – CSS chung
├── laning-content.css – CSS cho trang chủ
├── profile.css – CSS cho phần hồ sơ cá nhân
├── top-nav.css – CSS cho thanh điều hướng

**Cách Thay Đổi và Cập Nhật Nội Dung**

🔹 Chỉnh sửa dữ liệu:
Vào thư mục data và chỉnh sửa các tệp JavaScript tương ứng:

personal-data.js → Chỉnh sửa thông tin cá nhân.

projects-data.js → Cập nhật chi tiết về dự án.

services-data.js → Thay đổi thông tin dịch vụ.

📌 Cập nhật hình ảnh và biểu tượng:
Nếu muốn thay đổi hình ảnh hoặc biểu tượng, hãy đặt chúng vào thư mục thích hợp. Trong mã có chú thích hướng dẫn vị trí cho từng loại hình ảnh hoặc biểu tượng.

💡 Mọi thay đổi sẽ tự động được cập nhật vì nội dung được render động thông qua render-contents.js.

🎨 Cập nhật giao diện:

Mở thư mục style.

Chỉnh sửa các tệp CSS để điều chỉnh thiết kế và giao diện của website.

⚠️ Lưu ý quan trọng:
✅ Không xóa render-contents.js, vì nó tải dữ liệu động từ thư mục data.
✅ Giữ nguyên cấu trúc của các đối tượng JavaScript trong thư mục data để tránh lỗi.