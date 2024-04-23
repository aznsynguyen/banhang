- Xem version Django: 
- Tạo project mới: django-admin startproject mysite
- Chạy server: python manage.py runserver
- Đổi port: python manage.py runserver 6969
- Tạo app mới: python manage.py startapp polls
- Tạo mới, áp dụng sự thay đổi cho cơ sở dữ liệu: python manage.py migrate
- Tạo user mới: python manage.py createsuperuser
# Ap dụng MySQL
- Tạo database mới tại phpmyadmin
- Config database tai settings-py
- Chạy lệnh python manage.py migrate
* Xây dựng quản lý Category - Thêm sửa xoá đọc - CRUD
- python manage.py makemigrations news



sudo pkill mysqld
virtualenv venv
source venv/bin/activate
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Xong #13
Xong #13

