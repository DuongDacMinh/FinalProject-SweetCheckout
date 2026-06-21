# 🍰 SWEETCHECKOUT: Hệ Thống Trí Tuệ Nhân Tạo Nhận Diện & Thanh Toán Bánh Ngọt

![SweetCheckout Demo](Dán-link-tấm-hình-khay-bánh-bạn-vừa-up-lên-github-vào-đây)

## 📌 Giới thiệu Dự án
**SweetCheckout** là một ứng dụng AI tự động hóa quy trình thanh toán tại các tiệm bánh. Bằng việc ứng dụng Computer Vision và Deep Learning, hệ thống có khả năng tự động khoanh vùng, nhận diện các loại bánh trên khay và xuất hóa đơn thanh toán ngay lập tức với độ chính xác cao.

Dự án được phát triển nhằm mục đích ứng dụng công nghệ để giải quyết bài toán nghẽn cổ chai tại quầy thanh toán giờ cao điểm.

## ✨ Tính năng nổi bật
* **Object Localization:** Tự động cắt và khoanh vùng chính xác 5 vị trí ngăn chứa bánh trên khay inox chuẩn.
* **Image Classification:** Phân loại 10 dòng bánh ngọt phổ biến (Croissant, Bánh da lợn, Patechaud, Egg Tart...).
* **Real-time Billing:** Tự động cộng dồn giá tiền và xuất hóa đơn trực quan dưới dạng HTML ngay trên giao diện.
* **User-friendly UI:** Giao diện tương tác thân thiện được xây dựng bằng Gradio, hỗ trợ upload ảnh hoặc chụp trực tiếp từ webcam.

## 🛠 Công nghệ sử dụng
* **Ngôn ngữ:** Python
* **Deep Learning Framework:** TensorFlow / Keras (Mô hình CNN tự xây dựng)
* **Xử lý ảnh:** OpenCV (`cv2`), NumPy
* **Giao diện Web:** Gradio

## 🚀 Trải nghiệm ngay
Bạn có thể chạy thử hệ thống trực tiếp trên Google Colab mà không cần cài đặt môi trường phức tạp:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]((https://drive.google.com/file/d/1BqMTr9QFrm244THe6i7LV213jL7zpPMT/view?usp=sharing))

## 📦 Hướng dẫn cài đặt (Chạy Local)
Nếu muốn chạy trực tiếp trên máy cá nhân, vui lòng làm theo các bước sau:

1. **Clone repository:**
   ```bash
   git clone [https://github.com/DuongDacMinh/SweetCheckout-AI-Vision.git](https://github.com/DuongDacMinh/SweetCheckout-AI-Vision.git)
Cài đặt thư viện:

Bash
pip install tensorflow opencv-python numpy gradio

Tải file Model:

Do giới hạn dung lượng của GitHub, file sweetcheckout3final.keras được lưu trữ tại Google Drive.

👉 Tải file Model [tại đây](https://drive.google.com/file/d/1BqMTr9QFrm244THe6i7LV213jL7zpPMT/view?usp=sharing)

Đặt file vừa tải vào cùng thư mục với source code.

Chạy file Python: Mở file code và tiến hành khởi chạy giao diện.

Dự án kết thúc môn học Trí Tuệ Nhân Tạo - Hoàn thiện vào Tháng 6/2026.
