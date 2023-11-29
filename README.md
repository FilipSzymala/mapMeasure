# How to setup DistanceMeter backend

1. Install all needed dependencies (listed bellow)
2. Open XAMPP as an administrator (if you're using windows like system) or just give it all privilages needed and start 2 first services (Apache, MySQL)
3. In phpMyAdmin create new database (you can do that my clicking admin button in MySQL service in XAMPP)
4. Change name of .env.example to .env and change credentials of your database (default user is root without password)
5. Install composer in your project with command `composer install`
6. Generate your laravel app key with `php artisan key:generate`
7. Now run this command in your terminal or other cli `php artisan migrate` (it will change structure of your databse to one that you need)
8. Run your backend with this command `php artisan serve`

**Remeber, when CORS error occurs, to install anti-CORS like extension**

# needed dependencies

1. Node (https://nodejs.org/en)
2. XAMPP (https://www.apachefriends.org/)
3. Composer (https://getcomposer.org/download/)
