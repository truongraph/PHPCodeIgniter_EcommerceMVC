# 🛒 HỆ THỐNG QUẢN LÝ SHOPPING MALL

## ⚙️ CÔNG NGHỆ SỬ DỤNG

### 🔸 Front-End

* **HTML5**, **CSS3**
* **Bootstrap**
* **jQuery**, **AJAX**

### 🔸 Back-End

* **PHP + MySQL**
* **CodeIgniter Framework (ver 3.1.10)**
* **Mô hình MVC**

---

## 🗃️ CẤU HÌNH HỆ THỐNG

### 📂 Cơ sở dữ liệu

* File database: `shoppingmall.sql`

### ⚙️ Cấu hình đường dẫn

Mở file:
`application/config/config.php`

```php
$config['base_url'] = 'đường dẫn của máy hoặc host';
```

### ⚙️ Cấu hình kết nối Database

Mở file:
`application/config/database.php`

Điền các thông tin phù hợp với môi trường máy hoặc host của bạn.

---

## 🔑 TRUY CẬP TRANG QUẢN TRỊ

* **Đường dẫn**: `/admin`
* **Tài khoản quản trị**

  * Username: `admin`
  * Password: `123456`

---

## 💡 CHỨC NĂNG CHÍNH CỦA HỆ THỐNG

### 🛍️ FRONT-END

* Giao diện hiện đại, responsive chuẩn Bootstrap
* Đăng ký, đăng nhập thành viên
* Hiển thị:

  * Sản phẩm mới, khuyến mãi, bán chạy
  * Danh mục sản phẩm
  * Tin tức và tin tức mới nhất
* Tìm kiếm theo từ khóa
* Hiển thị nhiều hình ảnh và thông tin chi tiết sản phẩm
* Gợi ý sản phẩm cùng loại
* Đóng góp ý kiến và phản hồi tại trang **Liên hệ chúng tôi**
* Gửi **email đơn hàng** khi người dùng mua hàng
* Giỏ hàng:

  * Thêm sản phẩm, cập nhật số lượng, xóa sản phẩm
  * Đặt hàng có hoặc không cần tài khoản
  * Nhập **mã giảm giá** để được giảm trực tiếp
* Quản lý tài khoản:

  * Xem và theo dõi đơn hàng đã mua
  * Thông báo trạng thái đơn hàng
  * Hủy đơn hàng
  * Lấy lại mật khẩu / Đổi mật khẩu (có gửi email xác nhận)
* Khi **đăng ký tài khoản**, người dùng sẽ nhận **một mã giảm giá qua email**, chỉ sử dụng **1 lần**, hạn dùng **30 ngày** kể từ ngày đăng ký.

---

### 🧰 BACK-END (TRANG QUẢN TRỊ)

* **Quản lý nhà cung cấp** (Thêm, Sửa, Xóa, Cập nhật trạng thái, Nhập hàng)
* **Quản lý sản phẩm** (Thêm, Sửa, Xóa, Cập nhật trạng thái, Nhập hàng)
* **Quản lý bài viết** (Thêm, Sửa, Xóa, Cập nhật trạng thái)
* **Quản lý liên hệ** (Xem, Xóa)
* **Quản lý đơn hàng**

  * Xem chi tiết đơn hàng
  * Cập nhật trạng thái đơn hàng
  * Hủy / Lưu đơn hàng
* **Quản lý mã giảm giá** (Thêm, Sửa, Xóa)
* **Quản lý khách hàng** (Xem, Xóa)
* **Quản lý nhân viên** (Thêm, Sửa, Xóa, Lấy lại mật khẩu)
* **Quản lý Slider** (Xem, Sửa, Xóa)
* **Cấu hình phí giao hàng** (Sửa)
* **Cập nhật kho hàng**

  * Cập nhật số lượng sản phẩm khi đơn hàng hoàn tất
  * Cập nhật lượt sử dụng còn lại của mã giảm giá khi khách đặt hàng

---

## 💻 HƯỚNG DẪN CÀI ĐẶT VỚI XAMPP

1. Cài **XAMPP** (phiên bản PHP ≥ 7.2 khuyến nghị)
2. Sao chép toàn bộ thư mục dự án vào thư mục:

   ```
   C:\xampp\htdocs\
   ```
3. Mở **phpMyAdmin** → tạo database tên:

   ```
   shoppingmall
   ```
4. Import file `shoppingmall.sql` vào database vừa tạo
5. Cấu hình `config.php` và `database.php` như hướng dẫn trên
6. Chạy dự án bằng trình duyệt:

   ```
   http://localhost/tên-thư-mục-dự-án/
   ```
7. Truy cập trang quản trị:

   ```
   http://localhost/tên-thư-mục-dự-án/admin
   ```

---

## 📸 GIAO DIỆN HỆ THỐNG

![image](https://github.com/user-attachments/assets/2943181d-a87b-4ab0-b27f-24dfe5753f5f)
![image](https://github.com/user-attachments/assets/7e5bae27-359f-4661-9120-81cc19c28cbd)
![image](https://github.com/user-attachments/assets/3e3f54a9-7f0e-4582-a00e-a4ecdcb15f91)

---

### 🧾 Tác giả: *Võ Trường*
