# Airbnb-Clone

# 🏠 Airbnb Clone - Full Stack

Bản sao (Clone) của Airbnb được xây dựng hoàn toàn bằng các công nghệ hiện đại nhất. Dự án này bao gồm đầy đủ các tính năng từ xác thực người dùng, quản lý cơ sở dữ liệu, cho đến tính năng đặt phòng theo thời gian thực.

## 🚀 Công Nghệ Sử Dụng

Dự án được xây dựng dựa trên stack công nghệ mạnh mẽ và phổ biến nhất hiện nay:

* **Next.js 13 App Router:** Framework React cho hiệu suất cao (Server Components).
* **React:** Thư viện JavaScript để xây dựng giao diện người dùng.
* **TypeScript:** Ngôn ngữ lập trình bổ sung kiểu tĩnh (static typing) cho JavaScript.
* **Tailwind CSS:** Framework CSS utility-first để xây dựng giao diện nhanh chóng và linh hoạt.
* **Prisma:** ORM (Object-Relational Mapping) hiện đại để tương tác với cơ sở dữ liệu.
* **MongoDB:** Cơ sở dữ liệu NoSQL được sử dụng để lưu trữ dữ liệu ứng dụng.
* **NextAuth:** Thư viện xác thực toàn diện cho Next.js.

## ✨ Tính Năng Chính

Dự án bao gồm các tính năng cốt lõi sau:

* **Xác thực linh hoạt (Authentication):** Đăng nhập/Đăng ký qua Email/Password, Google, và GitHub (sử dụng NextAuth).
* **Quản lý Tài sản (Listings):**
    * Người dùng có thể tạo, chỉnh sửa và xóa tài sản của mình (nhà/phòng cho thuê).
    * Hỗ trợ tải lên hình ảnh tài sản.
* **Tìm kiếm và Lọc (Search & Filtering):**
    * Hệ thống tìm kiếm mạnh mẽ theo tên, địa điểm.
    * Bộ lọc nâng cao theo loại hình tài sản, số lượng khách, số phòng ngủ, v.v.
* **Đặt Phòng (Reservations):**
    * Người dùng có thể xem lịch khả dụng và đặt phòng.
    * Quản lý chuyến đi (Trips) đã đặt và các đặt chỗ mà người dùng đã nhận được.
* **Yêu thích (Favorites):** Lưu trữ các tài sản yêu thích của người dùng.
* **Giao diện đáp ứng (Responsive UI):** Đảm bảo trải nghiệm tuyệt vời trên mọi thiết bị (máy tính, máy tính bảng, điện thoại).

## 💻 Hướng Dẫn Cài Đặt và Chạy Dự Án

Để chạy dự án này trên máy cục bộ, làm theo các bước sau:

### 1. Yêu cầu Tiên quyết

* Node.js (Phiên bản LTS)
* Git
* Tài khoản MongoDB Atlas (hoặc môi trường MongoDB cục bộ)
* Tài khoản GitHub và Google Cloud (để thiết lập OAuth)

### 2. Thiết lập Dự án

```bash
# Clone repository
git clone <URL_Của_Repository>

# Di chuyển vào thư mục dự án
cd airbnb-clone

# Cài đặt các dependencies
npm install
