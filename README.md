# Xoá Font Trong File PDF

Công cụ web thuần **Client-side** giúp quét, gỡ bỏ dữ liệu font nhúng từ các tệp PDF nhằm **giảm dung lượng** tệp tin trực tiếp trên trình duyệt.

## ⚡ Điểm vượt trội

* **Tuyệt đối an toàn:** Không có backend, toàn bộ quá trình xử lý diễn ra trong RAM của máy cục bộ.
* **Cơ chế dự phòng:** Tự động chuyển sang file local nếu CDN gặp sự cố.
* **Dọn rác bộ nhớ:** Tự động giải phóng liên kết cũ (`URL.revokeObjectURL`) tránh tràn RAM.

## 🛠 Thông số kỹ thuật

| Thành phần | Chi tiết |
| --- | --- |
| **Công nghệ** | HTML5, CSS3, JavaScript (ES6+) |
| **Thư viện** | `pdf-lib` (v1.17.1) |
| **Môi trường** | Chạy offline hoặc online không cần cài đặt |

## 📁 Cấu trúc thư mục

```text
├── index.html          # Giao diện chính và logic xử lý
└── js/
    └── pdf-lib.min.js  # Thư viện dự phòng khi mất internet

```

## 🚀 Hướng dẫn sử dụng nhanh

* **Bước 1:** Kéo thả file `.pdf` vào vùng quy định hoặc click để chọn file.
* **Bước 2:** Chọn các font có nhãn **"Có dữ liệu nhúng"** từ danh sách hệ thống vừa quét được.
* **Bước 3:** Nhấn nút **"Gỡ Font đã chọn & Tải file về"** để nhận tệp tin đã tối ưu hóa.

## ⚠️ Lưu ý quan trọng

* Việc xoá font nhúng sẽ khiến file PDF sử dụng các font hệ thống thay thế. Hãy kiểm tra lại định dạng hiển thị sau khi trích xuất.

## 📄 Giấy phép

Dự án được bảo hộ bởi giấy phép **MIT License**.

## 👤 Tác giả

* **Dương Tấn Chánh**