# 🏃‍♂️ VSM - Vietnam Student Marathon (Mobile App)

## 📌 Giới thiệu
VSM – Vietnam Student Marathon là ứng dụng chạy bộ dành cho sinh viên và cộng đồng yêu thích chạy bộ tại Việt Nam.  
Ứng dụng hỗ trợ theo dõi buổi chạy, lưu lịch sử, xếp hạng, lập kế hoạch, và tham gia các sự kiện thể thao.

Hiện tại dự án đang ở **giai đoạn lập kế hoạch** và sẽ phát triển phiên bản **mobile** đầu tiên bằng **React Native**.

---

## 🛠 Công nghệ dự kiến sử dụng

### **Frontend (Mobile)**
- **React Native** – Xây dựng ứng dụng mobile đa nền tảng (Android & iOS) từ cùng một codebase.
- **Expo** (dự kiến) – Hỗ trợ phát triển nhanh, tích hợp sẵn nhiều API (camera, location, push notifications…).
- **React Navigation** – Quản lý điều hướng giữa các màn hình.
- **Redux Toolkit** hoặc **React Query** – Quản lý trạng thái & đồng bộ dữ liệu với backend.
- **Axios** – Gọi API từ backend.
- **Mapbox** hoặc **React Native Maps** – Hiển thị bản đồ và đường chạy.
- **Victory Native** hoặc **Recharts** – Hiển thị biểu đồ thống kê.
- **AsyncStorage** – Lưu dữ liệu cục bộ (token, cài đặt giao diện…).
- **Firebase Cloud Messaging (FCM)** – Push notification nhắc nhở chạy bộ.
- **Google & Facebook SDK** – Đăng nhập mạng xã hội.

### **Backend** (sẽ kết nối sau)
- **NestJS / Node.js** – Backend API.
- **PostgreSQL / MongoDB** – Lưu trữ dữ liệu người dùng & hoạt động chạy bộ.
- **Prisma ORM** – Quản lý database.
- **Auth JWT** – Xác thực người dùng.

---

## 🚀 Tính năng dự kiến

### **Guest (Chưa đăng nhập)**
- Đăng nhập / Đăng ký (Email, Facebook, Google).
- Xem trang chủ (Sự kiện & Tin tức nổi bật).
- Xem chi tiết sự kiện, tin tức.
- Xem bảng xếp hạng tuần/tháng.
- Xem lộ trình chạy mẫu.
- Chỉnh chế độ giao diện (Dark / Light mode).
- Đổi ngôn ngữ.
- Xem giới thiệu ứng dụng.

### **User (Đã đăng nhập)**
- Kế thừa toàn bộ tính năng Guest.
- Làm bài test thể trạng (cân nặng, chiều cao) để cá nhân hóa lộ trình chạy.
- Theo dõi buổi chạy (GPS tracking, thời gian, tốc độ, khoảng cách).
- Lưu & xem lịch sử chạy bộ.
- Hiển thị bản đồ đường chạy.
- Quản lý hồ sơ cá nhân.
- Xem thống kê (ngày, tuần, tháng).
- Xây dựng kế hoạch chạy bộ cá nhân.
- Đặt mục tiêu cá nhân.
- Nhận thông báo nhắc nhở chạy.
- Ghi chú cảm xúc sau buổi chạy.

### **VIP User**
- Kế thừa toàn bộ tính năng User.
- Tính năng nâng cao:
  - Lộ trình huấn luyện nâng cao.
  - Phân tích hiệu suất chuyên sâu.
  - Sự kiện độc quyền cho VIP.


---

## 📅 Lộ trình phát triển (dự kiến)

1. **Giai đoạn 1** – Thiết kế UI/UX & dựng cấu trúc dự án React Native.
2. **Giai đoạn 2** – Hoàn thiện các màn hình cơ bản (Guest).
3. **Giai đoạn 3** – Tích hợp tính năng User (theo dõi chạy, thống kê…).
4. **Giai đoạn 4** – Tích hợp VIP features & tối ưu hiệu năng.
5. **Giai đoạn 5** – Test toàn bộ app và publish lên Google Play / App Store.

---

## 👥 Đối tượng sử dụng
- Sinh viên, học sinh, cộng đồng yêu thích chạy bộ.
- Các vận động viên tham gia sự kiện **Vietnam Student Marathon**.
- Người dùng muốn quản lý lộ trình chạy bộ cá nhân.

---

## 📌 Ghi chú
- Đây là bản kế hoạch ban đầu, các công nghệ và tính năng có thể được điều chỉnh trong quá trình phát triển.
- Mọi thành viên mới vào nhóm cần đọc file này trước khi bắt đầu code.

