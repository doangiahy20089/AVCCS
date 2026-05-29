🛡️ AVCCS - An Toàn Số Hôm Nay, Bảo Vệ Tương Lai Ngày Mai

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployment-brightgreen?style=flat-square&logo=github)](https://doangiahy20089.github.io/AVCCS/)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://doangiahy20089.github.io/AVCCS/)
[![Topic](https://img.shields.io/badge/Topic-Cybersecurity%20Education-red?style=flat-square)]()

**AVCCS (Cyber Security Awareness)** là một nền tảng giáo dục trực tuyến trực quan và tương tác, được thiết kế nhằm nâng cao nhận thức về an toàn thông tin dành cho học sinh, sinh viên và cộng đồng. Dự án giúp người dùng dễ dàng nhận diện các hình thức lừa đảo, lỗ hổng bảo mật phổ biến và trang bị các kỹ năng cốt lõi để tự bảo vệ mình trong không gian số.

🌍 **Trải nghiệm ứng dụng tại:** [https://doangiahy20089.github.io/AVCCS/](https://doangiahy20089.github.io/AVCCS/)

---

## 🚀 Các Tính Năng Nổi Bật

### 1. Mô Phỏng Tình Huống Thực Tế (Interactive Simulation)
Giúp người dùng tương tác trực tiếp với các kịch bản tấn công mạng quen thuộc để rút ra bài học:
* **🔍 Nhận diện Link Giả:** Phân tích cấu trúc domain độc hại (ví dụ: `vietcombankupdate.xyz`) và các dấu hiệu tạo áp lực tâm lý.
* **🔒 Phân Tích Độ Mạnh Mật Khẩu:** Đo lường và kiểm tra mật khẩu theo thời gian thực (Độ dài, chữ hoa, chữ số, ký tự đặc biệt).
* **💬 Mô phỏng Tấn Công XSS:** Thử nghiệm nhúng mã độc JavaScript (`<script>`) vào form bình luận và quan sát cơ chế chặn/lọc (Sanitization) của hệ thống.
* **📱 OTP Scam:** Kịch bản mạo danh bạn bè trên mạng xã hội để chiếm đoạt mã xác thực OTP thông qua tin nhắn.

### 2. Hệ Thống Gamification & Dashboard Cá Nhân
* **Cơ chế tính điểm:** Hoàn thành các tình huống và bài kiểm tra để tích lũy điểm kinh nghiệm (**XP**) và nâng cấp danh hiệu (ví dụ: *Level 1 - Beginner*).
* **Thống kê trực quan:** Theo dõi tiến độ học tập phân chia theo từng chủ đề: Phishing, Link giả, Mật khẩu, Mạng xã hội, Dữ liệu.

### 3. Trung Tâm Kiến Thức (Knowledge Base)
Cung cấp các phân tích học thuật chuyên sâu nhưng dễ hiểu về tam giác bảo mật **CIA**, các thuật ngữ nâng cao như **SQL Injection**, **OSINT**, **Data Breach**, **VPN** và xu hướng lừa đảo công nghệ cao bằng **Deepfake**.

### 4. Công Cụ Scan URL & Quiz Trắc Nghiệm
* **URL Scanner Demo:** Cho phép người dùng nhập thử các đường dẫn nguy hiểm (`freegift2024.xyz`, `win-now.ru`) để nhận cảnh báo tức thì.
* **Hệ thống Quiz:** Bộ câu hỏi đa dạng theo từng chủ đề, tích hợp chấm điểm tự động để củng cố kiến thức.

---

## 🛠️ Công Nghệ Sử Dụng

Dự án được xây dựng tối ưu theo mô hình giao diện Single Page Application (SPA) mượt mà bằng các công nghệ web cốt lõi:
* **HTML5 & CSS3:** Cấu trúc ngữ nghĩa rõ ràng, giao diện hiện đại với tone màu tối (Dark Mode) chủ đạo phối hợp cùng các màu sắc cảnh báo trực quan (Xanh bảo mật, Đỏ nguy hiểm).
* **JavaScript (ES6+):** Xử lý toàn bộ logic tương tác, chấm điểm Quiz, kiểm tra mật khẩu, quét URL và cập nhật trạng thái Dashboard Client-side (không cần reload trang).
* **Responsive Web Design:** Tương thích hoàn hảo trên các thiết bị máy tính (Desktop), máy tính bảng (Tablet) và điện thoại di động (Mobile).

---

## 📂 Cấu Trúc Thư Mục Dự Án

```text
AVCCS/
├── index.html          # File giao diện chính tích hợp toàn bộ các module của SPA
├── css/                # Chứa các file style định dạng giao diện (nếu có tách riêng)
├── js/                 # Chứa các file script xử lý logic tính năng (nếu có tách riêng)
└── README.md           # Tài liệu giới thiệu dự án (File này)
