## Project Chat room 
Xây dựng ứng dụng chat Room real time với Pusher
Các chức năng chính:
+ Đăng nhập/ Đăng ký tài khoản
+ Tạo, sửa, xóa, Join vào một phòng chat (Room)
+ Xem thông tin phòng, thành viên trong phòng chat
+ Nhắn tin trong phòng với nhau

## Cài đặt project
1. Clone project về máy
```commandline
    git clone https://github.com/HuyHoang2358/TechMaster-ChatRoom.git
```
2. Cài đặt composer
```commandline
    cd project
    composer install
    Hoặc
    composer update
```
3. Cài đặt thư viện npm
```commandline
    npm install
```
4. Tạo file .env từ file .env.example
```commandline
    cp .env.example .env
```
5. Tạo key cho project
```commandline
    php artisan key:generate
```
6. Cấu hình database trong file .env
```commandline
    DB_CONNECTION=mysql
    DB_HOST=
    DB_PORT=
    DB_DATABASE=
    DB_USERNAME=
    DB_PASSWORD=
```
7. Chạy migration
```commandline
    php artisan migrate
```
8. Chạy server
```commandline
    php artisan serve
```


