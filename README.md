# BTL_Quan_Ly_CLB
<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>
<h2 align="center">
    Club management
</h2>
<div align="center">
    <p align="center">
        <img src="docs/logo/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/logo/fitdnu_logo.png" alt="AIoTLab Logo" width="180"/>
        <img src="docs/logo/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

</div>
 
## 📖 1. Giới thiệu
Hệ thống Quản lý Câu lạc bộ trong trường Đại học được xây dựng nhằm hỗ trợ công tác quản lý, theo dõi và đánh giá hoạt động của các Câu lạc bộ trong môi trường giáo dục đại học. Thay vì quản lý thủ công bằng giấy tờ hay các tệp Excel rời rạc, hệ thống mang đến một giải pháp tập trung, hiện đại và dễ sử dụng.

## 🔧 2. Các công nghệ được sử dụng
<div align="center">

### Hệ điều hành
![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
[![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/en-us/windows/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://ubuntu.com/)

### Công nghệ chính
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

### Web Server & Database
[![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)](https://httpd.apache.org/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/) 
[![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)](https://www.apachefriends.org/)

### Database Management Tools
[![MySQL Workbench](https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://dev.mysql.com/downloads/workbench/)
</div>

## 🚀 3. Hình ảnh các chức năng
### Trang đăng nhập
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6835c09d-9fa7-4b83-8d3d-bdbcf78b1d31" />

### Trang chủ
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/64f82009-540f-4e4b-9966-b5d0645fa60d" />

## ⚙️ 4. Cài đặt

### 4.1. Cài đặt công cụ, môi trường và các thư viện cần thiết

- Tải và cài đặt **XAMPP**  
  👉 https://www.apachefriends.org/download.html  
  (Khuyến nghị bản XAMPP với PHP 8.x)

- Cài đặt **Visual Studio Code** và các extension:
  - PHP Intelephense  
  - MySQL  
  - Prettier – Code Formatter

# 🎓 HỆ THỐNG QUẢN LÝ CÂU LẠC BỘ

## 📋 Giới Thiệu

Đây là bài tập lớn môn **Mã Nguồn Mở**, xây dựng hệ thống quản lý câu lạc bộ sinh viên với đầy đủ tính năng từ quản lý thành viên, sự kiện, tài chính đến điểm danh QR Code.

### 🎯 Mục Tiêu
- Áp dụng công nghệ mã nguồn mở (XAMPP, PHP, MySQL, Bootstrap)
- Xây dựng ứng dụng web thực tế, đầy đủ chức năng
- Thực hành Git, MySQL Workbench, Terminal Commands


## 🚀 Công Nghệ Sử Dụng

### Backend
- **PHP 8.x** - Server-side scripting
- **MySQL/MariaDB** - Database management
- **Apache** - Web server (XAMPP)

### Frontend
- **HTML5** - Structure
- **CSS3** - Styling
- **JavaScript** - Interactivity
- **Bootstrap 5** - Responsive framework
- **Font Awesome 6** - Icons

### Tools
- **XAMPP** - Development environment
- **MySQL Workbench** - Database design
- **Git** - Version control
- **HTML5-QRCode** - QR scanning library

---

## 📁 Cấu Trúc Thư Mục

```
CLUB_MANAGEMENT/
├── admin/                      # Module quản trị viên
│   ├── index.php              # Dashboard admin
│   ├── clubs.php              # Quản lý CLB
│   ├── users.php              # Quản lý người dùng
│   ├── events.php             # Duyệt sự kiện
│   ├── finances.php           # Duyệt tài chính
│   ├── reports.php            # Báo cáo tổng hợp
│   └── includes/
│       ├── header.php         # Header & sidebar
│       └── footer.php         # Footer
│
├── leader/                     # Module chủ nhiệm CLB
│   ├── index.php              # Dashboard leader
│   ├── members.php            # Quản lý thành viên
│   ├── events.php             # Quản lý sự kiện
│   ├── event_detail.php       # Chi tiết sự kiện
│   ├── event_qr.php           # QR Code điểm danh
│   ├── get_attendance_stats.php # API thống kê
│   ├── finances.php           # Quản lý tài chính
│   ├── notifications.php      # Gửi thông báo
│   ├── reports.php            # Báo cáo
│   └── club_info.php          # Thông tin CLB
│
├── member/                     # Module sinh viên
│   ├── index.php              # Dashboard member
│   ├── clubs.php              # Danh sách & tham gia CLB
│   ├── events.php             # Xem & đăng ký sự kiện
│   ├── scan_qr.php            # Quét QR điểm danh
│   ├── my_activities.php      # Thống kê hoạt động
│   ├── notifications.php      # Thông báo
│   └── profile.php            # Hồ sơ cá nhân
│
├── config/
│   ├── database.php           # Kết nối database
│   └── functions.php          # Hàm hỗ trợ
│
├── uploads/                    # Thư mục lưu file
│   ├── avatars/               # Ảnh đại diện
│   ├── logos/                 # Logo CLB
│   └── receipts/              # Hóa đơn
│
├── index.php                   # Landing page
├── login.php                   # Đăng nhập
├── register.php                # Đăng ký
├── logout.php                  # Đăng xuất
├── database.sql                # File SQL database
└── README.md                   # File này
```

---

## 💾 Cài Đặt & Chạy Dự Án

### Bước 1: Chuẩn Bị Môi Trường

#### 1.1. Cài đặt XAMPP trên Ubuntu
```bash
# Tải XAMPP
wget https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run

# Phân quyền thực thi
chmod +x xampp-linux-x64-8.2.12-0-installer.run

# Cài đặt
sudo ./xampp-linux-x64-8.2.12-0-installer.run

# Khởi động XAMPP
sudo /opt/lampp/lampp start
```

#### 1.2. Cài đặt MySQL Workbench
```bash
# Ubuntu/Debian
sudo apt update
sudo apt install mysql-workbench

# Hoặc dùng snap
sudo snap install mysql-workbench-community
```

#### 1.3. Cài đặt Git
```bash
sudo apt install git
```

### Bước 2: Clone & Setup Dự Án

```bash
# Di chuyển đến thư mục htdocs
cd /opt/lampp/htdocs

# Clone project (nếu có Git repo)
git clone [URL_REPO] club_management

# Hoặc copy thủ công
sudo cp -r /path/to/CLUB_MANAGEMENT /opt/lampp/htdocs/club_management
```

### Bước 3: Tạo Database

#### Option 1: Dùng phpMyAdmin
1. Truy cập: `http://localhost/phpmyadmin`
2. Tạo database tên `club_management`
3. Import file `database.sql`

#### Option 2: Dùng Terminal
```bash
# Login MySQL
mysql -u root -p

# Tạo database
CREATE DATABASE club_management CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

# Import file SQL
mysql -u root -p club_management < /path/to/database.sql
```

### Bước 4: Cấu Hình Database Connection

Chỉnh sửa file `config/database.php`:

```php
<?php
$host = 'localhost';
$dbname = 'club_management';
$username = 'root';   
$password = '';     

$conn = new mysqli($host, $username, $password, $dbname);
$conn->set_charset("utf8mb4");

if ($conn->connect_error) {
    die("Kết nối thất bại: " . $conn->connect_error);
}
?>
```

### Bước 5: Tạo Thư Mục Uploads

```bash
cd /opt/lampp/htdocs/club_management

# Tạo thư mục
mkdir -p uploads/avatars uploads/logos uploads/receipts

# Phân quyền
chmod -R 777 uploads/
```

### Bước 6: Chạy Ứng Dụng

1. Truy cập: `http://localhost/club_management`
2. Hoặc: `http://127.0.0.1/club_management`

---

## 👤 Tài Khoản Demo

### Admin
- **Username:** admin
- **Password:** admin123
- **Quyền:** Quản lý toàn hệ thống

### Leader (Chủ nhiệm CLB)
- **Username:** leader1
- **Password:** leader123
- **Quyền:** Quản lý CLB được gán

### Member (Sinh viên)
- **Username:** member1
- **Password:** member123
- **Quyền:** Tham gia CLB, đăng ký sự kiện

---

## 🎨 Tính Năng Chính

### 🔐 Hệ Thống Phân Quyền
- **Admin**: Quản lý toàn bộ hệ thống
- **Leader**: Quản lý CLB của mình
- **Member**: Tham gia hoạt động

### Phần Admin:
1. Dashboard (index.php)

Thống kê tổng quan
Hiển thị CLB mới nhất
Sự kiện chờ duyệt
Giao diện đẹp với sidebar

2. Quản Lý CLB (clubs.php)

✅ Thêm CLB mới
✅ Sửa thông tin CLB
✅ Xóa CLB
✅ Hiển thị số thành viên và sự kiện
✅ Modal Bootstrap đẹp
✅ AJAX để load dữ liệu

3. Quản Lý Chủ Nhiệm (leaders.php)

✅ Thêm chủ nhiệm cho CLB
✅ Xóa chủ nhiệm
✅ Tự động cập nhật role user
✅ Kiểm tra trùng lặp

4. Phê Duyệt (approvals.php)

✅ Duyệt/Từ chối sự kiện
✅ Duyệt/Từ chối đơn xin vào CLB
✅ Duyệt/Từ chối kế hoạch hoạt động
✅ Tabs navigation
✅ Tạo thông báo tự động

5. Quản Lý Người Dùng (users.php)

✅ Danh sách tất cả user
✅ Tìm kiếm và lọc
✅ Bật/Tắt trạng thái user
✅ Xóa user
✅ Pagination
✅ Thống kê

6. Báo Cáo (reports.php)

✅ Thống kê tổng quan
✅ Top 5 CLB nhiều thành viên
✅ CLB theo danh mục
✅ Sự kiện theo tháng
✅ Tổng quan tài chính
✅ In báo cáo

🎯 Các Files Hỗ Trợ:

✅ get_club.php - AJAX lấy thông tin CLB
✅ logout.php - Đăng xuất


## 📊 Database Schema

### Bảng Chính

#### users
```sql
user_id, username, password, full_name, email, phone, avatar, role, status, created_at
```

#### clubs
```sql
club_id, club_name, description, logo, leader_id, budget, status, created_at
```

#### club_members
```sql
member_id, club_id, user_id, join_date, status, role_in_club, created_at
```

#### events
```sql
event_id, club_id, event_name, description, event_date, start_time, end_time, 
location, max_participants, budget, status, qr_code, created_by, created_at
```

#### event_registrations
```sql
registration_id, event_id, user_id, registration_date, status, attendance_time
```

#### finances
```sql
finance_id, club_id, transaction_type, amount, description, transaction_date, 
category, status, created_by, approved_by, receipt_image, created_at
```

#### notifications
```sql
notification_id, user_id, title, content, type, is_read, link, created_at
```

---

## 🐛 Xử Lý Lỗi Thường Gặp

### 1. Không kết nối được database
```bash
# Kiểm tra MySQL đang chạy
sudo /opt/lampp/lampp status

# Khởi động lại MySQL
sudo /opt/lampp/lampp reloadmysql
```

### 2. Không upload được file
```bash
# Kiểm tra quyền
ls -la uploads/

# Sửa quyền
chmod -R 777 uploads/
```

### 3. QR Code không hiển thị
- Kiểm tra kết nối internet (dùng API online)
- Hoặc tải thư viện html5-qrcode về local

### 4. Session timeout
Chỉnh sửa `php.ini`:
```ini
session.gc_maxlifetime = 3600
session.cookie_lifetime = 3600
```

### 5. Lỗi 404 Not Found
Kiểm tra file `.htaccess` hoặc cấu hình Apache

---


## 🔄 Git Commands Cơ Bản

```bash
# Clone repo
git clone [URL]

# Xem trạng thái
git status

# Add files
git add .

# Commit
git commit -m "Message"

# Push
git push origin main

# Pull
git pull origin main

# Tạo branch mới
git checkout -b feature-name

# Merge branch
git merge feature-name
```

---

## 📸 Screenshots

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### Leader Events Management
![Leader Events](screenshots/leader-events.png)

### Member QR Scan
![QR Scan](screenshots/member-qr-scan.png)


## 🎓 Kiến Thức Áp Dụng

### Mã Nguồn Mở
- ✅ XAMPP (Apache, MySQL, PHP)
- ✅ Bootstrap framework
- ✅ Font Awesome icons
- ✅ HTML5-QRCode library
- ✅ Git version control

### Web Development
- ✅ MVC pattern (cơ bản)
- ✅ RESTful design
- ✅ Session management
- ✅ File upload handling
- ✅ AJAX/API calls

### Database
- ✅ Relational database design
- ✅ SQL queries
- ✅ Joins & aggregations
- ✅ Indexing
- ✅ Transactions

---

## 📄 License

Dự án này được phát triển cho mục đích học tập (Bài Tập Lớn Môn Mã Nguồn Mở).

---

## 🙏 Tài Liệu Tham Khảo

1. [PHP Documentation](https://www.php.net/docs.php)
2. [MySQL Documentation](https://dev.mysql.com/doc/)
3. [Bootstrap Documentation](https://getbootstrap.com/docs/)
4. [HTML5-QRCode](https://github.com/mebjas/html5-qrcode)
5. [Font Awesome](https://fontawesome.com/)

---

## ✨ Tính Năng Có Thể Mở Rộng

- [ ] Email notifications
- [ ] SMS notifications
- [ ] Export Excel/PDF thực sự
- [ ] Real-time chat
- [ ] Mobile app (React Native)
- [ ] API documentation (Swagger)
- [ ] Docker deployment
- [ ] CI/CD pipeline

### 4.2. Tải project
Clone project về thư mục `htdocs` của XAMPP (ví dụ ổ C):

```bash
cd C:\xampp\htdocs
https://github.com/tyanzuq2811/BTL_Quan_ly_doan_vien.git
Truy cập project qua đường dẫn:
👉 http://localhost/authentication_login.
```
### 4.3. Setup database
Mở XAMPP Control Panel, Start Apache và MySQL

Truy cập MySQL WorkBench
Tạo database:
```bash
CREATE DATABASE IF NOT EXISTS club_management
   CHARACTER SET utf8mb4
   COLLATE utf8mb4_unicode_ci;
```

### 4.4. Setup tham số kết nối
Mở file config.php (hoặc .env) trong project, chỉnh thông tin DB:
```bash

<?php
    function getDbConnection() {
        $servername = "localhost";
        $username = "root";
        $password = "";
        $dbname = "club_management";
        $port = 3306;
        $conn = mysqli_connect($servername, $username, $password, $dbname, $port);
        if (!$conn) {
            die("Kết nối database thất bại: " . mysqli_connect_error());
        }
        mysqli_set_charset($conn, "utf8");
        return $conn;
    }
?>
```
### 4.5. Chạy hệ thống
Mở XAMPP Control Panel → Start Apache và MySQL

Truy cập hệ thống:
👉 http://localhost/index.php

