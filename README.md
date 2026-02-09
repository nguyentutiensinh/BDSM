# 🧩 BDSM – Base Demand Support Modeling for Blender

**BDSM** (Base Demand Support Modeling) là một tiện ích mở rộng (extension) dành cho phần mềm **Blender**, hỗ trợ người dùng tạo và quản lý các mô hình hỗ trợ (support structures) cho in 3D hoặc mô phỏng vật lý. Dự án được phát triển nhằm đơn giản hóa quy trình dựng hình nền móng, giá đỡ, hoặc các cấu trúc phụ trợ trong các dự án thiết kế kỹ thuật số.

---

## 🎯 Mục đích

Trong các ứng dụng như in 3D, mô phỏng vật lý hoặc dựng hình kỹ thuật, việc tạo các cấu trúc hỗ trợ là điều không thể thiếu. BDSM giúp:

- Tự động hóa quá trình tạo support structures
- Tùy biến hình dạng, vị trí và mật độ hỗ trợ
- Tăng hiệu quả dựng hình và tối ưu hóa mô hình cho in 3D

---

## ⚙️ Yêu cầu hệ thống

- **Blender**: phiên bản 3.0 trở lên
- **Python**: đi kèm với Blender (không cần cài đặt riêng)
- Hệ điều hành: Windows / macOS / Linux

---

## 📦 Cài đặt

### 1. Tải extension

Tải file `.zip` mới nhất từ trang phát hành:

🔗 [Releases – github.com/nguyentutiensinh/BDSM/releases](https://github.com/nguyentutiensinh/BDSM/releases)

### 2. Cài đặt trong Blender

1. Mở Blender
2. Vào menu: `Edit` → `Preferences` → `Add-ons`
3. Nhấn nút **Install...**
4. Chọn file `bdsm.zip` vừa tải về
5. Tìm “BDSM” trong danh sách add-ons và đánh dấu chọn để kích hoạt

---

## 🚀 Sử dụng

Sau khi cài đặt, bạn sẽ thấy một tab mới trong giao diện Blender:

### 🔧 Các tính năng chính:

- **Add Support Base**: Tạo nền móng hoặc giá đỡ cho mô hình hiện tại
- **Auto Support Generation**: Tự động phân tích và tạo support dựa trên hình học
- **Custom Parameters**: Tùy chỉnh chiều cao, độ dày, góc nghiêng và mật độ support
- **Export for 3D Printing**: Xuất mô hình kèm support sang định dạng STL/OBJ

### 📌 Hướng dẫn nhanh:

1. Chọn đối tượng cần tạo support
2. Vào tab `BDSM` trong thanh công cụ bên phải
3. Nhấn **Generate Support**
4. Tùy chỉnh thông số nếu cần
5. Nhấn **Apply** để hoàn tất

---

## 🧠 Gợi ý sử dụng

- Kết hợp với **Blender Physics** để kiểm tra độ ổn định của support
- Dùng **Subdivision Surface** để làm mịn support nếu cần in chất lượng cao
- Có thể dùng cho cả mô hình kiến trúc, nhân vật, hoặc cơ khí

---

## 🤝 Đóng góp

Mọi đóng góp đều được hoan nghênh! Bạn có thể:

- Gửi [issue](https://github.com/nguyentutiensinh/BDSM/issues) nếu phát hiện lỗi
- Gửi pull request để cải tiến tính năng
- Đề xuất ý tưởng mới cho cộng đồng

---

## 📜 Giấy phép

Dự án được phát hành theo giấy phép **GPL‑3.0 License** – bạn có thể sử dụng, chỉnh sửa và phân phối tự do.

---

## 📬 Liên hệ

Người phát triển: [@nguyentutiensinh](https://github.com/nguyentutiensinh)  
Email: nguyentutiensinh@gmail.com

> Cảm ơn bạn đã sử dụng BDSM – chúc bạn dựng hình vững chắc, mô hình vững vàng!
