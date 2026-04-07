# ☕ Coffee Mocha – UX Design (Khách hàng & Admin)

## 1. Tổng quan (Overview)
Website cho phép khách hàng khám phá menu, tìm kiếm đồ uống và đặt hàng trực tuyến một cách nhanh chóng.

**Mục tiêu:**
* Tăng trải nghiệm người dùng thông qua giao diện trực quan.
* Tối ưu hóa quy trình tìm kiếm và đặt món.
* Cung cấp hệ thống quản lý (Admin) hiệu quả cho chủ quán.

---

## 2. Đối tượng người dùng (Target Users)
* **Giới trẻ:** Ưa chuộng sự tiện lợi, công nghệ và giao diện bắt mắt.
* **Tín đồ cà phê:** Những người quan tâm đến chi tiết món và trải nghiệm thưởng thức.
* **Khách hàng bận rộn:** Muốn đặt đồ nhanh, không cần chờ đợi tại quầy.

---

## 3. Các tính năng chính (Main Features)
* 🔍 **Tìm kiếm:** Tìm nhanh đồ uống theo tên.
* 📑 **Menu phân loại:** Xem danh mục sản phẩm khoa học.
* 🛒 **Giỏ hàng:** Thêm/bớt món, xem tổng tiền thời gian thực.
* 📦 **Đặt hàng:** Quy trình thanh toán/xác nhận đơn giản.
* 📊 **Admin Dashboard:** Quản lý đơn hàng, cập nhật trạng thái và điều chỉnh menu.

---

## 4. Cấu trúc chi tiết & Trải nghiệm người dùng (UX)

### 4.1 Trang Chủ (Home Page)
* **Hero Section:** Hình ảnh không gian quán tạo cảm xúc + Tiêu đề "Khám Phá Cà Phê Hoàn Hảo".
* **Thanh tìm kiếm:** Đặt tại trung tâm để người dùng hành động ngay.
* **UX Decision:** Hình ảnh đẹp giúp giữ chân người dùng (Retention rate) và thanh tìm kiếm trung tâm giúp giảm ma sát khi bắt đầu sử dụng.

### 4.2 Danh mục sản phẩm (Category Menu)
* **Phân loại theo mùa:** Xuân, Hạ, Thu, Đông.
* **UX Decision:** Sử dụng icon và màu sắc đặc trưng cho từng mùa giúp người dùng dễ nhận diện và khám phá menu theo cảm xúc/thời tiết.

### 4.3 Hiển thị sản phẩm (Product Display)
* Thông tin hiển thị: Tên món, Giá, Trạng thái đơn hàng.
* **UX Decision:** Thiết kế tối giản, tập trung vào hình ảnh sản phẩm để tránh gây quá tải thông tin (Information Overload).

### 4.4 Giỏ hàng & Profile
* **Giỏ hàng (Bên phải):** Luôn hiển thị icon nổi, dễ dàng truy cập bất cứ lúc nào.
* **User Profile:** Lưu trữ lịch sử đơn hàng và thông tin cá nhân.

---

### 4.5 Giao diện Quản trị (Admin Dashboard)
Hệ thống dành riêng cho chủ quán để vận hành và kiểm soát dữ liệu.

* **Quản lý Đơn hàng:** Bảng hiển thị ID, sản phẩm, tổng tiền.
* **Trạng thái màu sắc:** * 🟠 Màu cam: Chờ duyệt.
    * 🟢 Màu xanh: Hoàn thành.
* **UX Decision:** Thiết kế dạng bảng tối giản (Efficiency) giúp Admin xử lý hàng chục đơn hàng mà không cần cuộn trang quá nhiều.

---

## 5. Luồng người dùng (User Flow)
`Vào Web` ➔ `Tìm kiếm/Chọn món` ➔ `Thêm vào giỏ` ➔ `Kiểm tra đơn` ➔ `Xác nhận đặt hàng` ➔ `Admin duyệt đơn` ➔ `Hoàn thành`.

---

## 6. Đề xuất nâng cấp (UX Improvements)
* [ ] **Bộ lọc nâng cao:** Lọc theo giá cả, mức độ phổ biến.
* [ ] **Đánh giá:** Cho phép khách hàng để lại feedback về món ăn.
* [ ] **Gợi ý thông minh:** "Món này thường được mua kèm với..." (Cross-selling).
* [ ] **Thông báo:** Cải thiện thông báo lỗi/hết món theo hướng thân thiện hơn.

---

## 7. Phát triển trong tương lai
* Tích hợp cổng thanh toán Online (VNPay, Momo).
* Hệ thống tích điểm thành viên (Loyalty Program).
* Cá nhân hóa menu dựa trên sở thích cũ của khách hàng.