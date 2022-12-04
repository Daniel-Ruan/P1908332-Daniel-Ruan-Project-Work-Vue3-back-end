## P1908332 Daniel Ruan Project API
A Product CRUD Application API. It's included with JWT authentication and Swagger API format.

----

### Language:
1. PHP-8
1. Laravel-9

### API List:
##### Authentication Module
1. Register User API with Token
1. Login API with Token
1. Authenticated User Profile
1. Refresh Data
1. Logout

##### Product Module
1. Product List
1. Product List [Public]
1. Create Product
1. Edit Product
1. View Product
1. Delete Product

### How to Run:
```bash
git clone https://github.com/Daniel-Ruan/P1908332-Daniel-Ruan-Project-Work-Vue3-back-end.git
```
1. Install php8 https://windows.php.net/download, 中文参考如下 https://10.1pxeye.com/install-php-8-on-windows-with-apache/
2. Install Composer 环境变量设置与php相同
3. Install laravel9 framework https://laravel.com/docs/9.x
4. Download code ZIP, and unzip. 
5. Go to the project directory by `cd ` 
6. Create `.env` file & Copy `.env.example` file to `.env` file
7. Install XAMPP https://www.apachefriends.org/
8. ![1](D:\laravel\1.png)
9. ![2](D:\laravel\2.png)
10. Create a database called - `laravel_basic_crud`.
11. Install composer packages - `composer install`.
12. Now migrate and seed database to complete whole project setup by running this-
``` bash
php artisan migrate:refresh --seed
```
13. Generate Swagger API

``` bash
php artisan l5-swagger:generate
```
14. Run the server -

``` bash
php artisan serve
```
15. Open Browser -
    http://127.0.0.1:8000 & go to API Documentation -

### Demo

![demoAPI](D:\laravel\demoAPI.png).
