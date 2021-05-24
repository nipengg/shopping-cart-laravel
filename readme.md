## Shopping Cart Laravel
Basic Shopping Cart with Laravel

## Spesifikasi
- PHP ^7.2
- Laravel 5.5.x
- Database MySQL atau MariaDB

### Instalasi

1. Clone atau download source code
    - Para terminal, clone repo `git clone https://github.com/nipengg/shopping-cart-laravel.git`
    - Jika tidak menggunakan Git, silakan **Download Zip** dan *extract* pada direktori web server (misal: xampp/htdocs)
2. `cd shopping-cart-laravel`
3. `composer install`
4. `cp .env.example .env`
    - Jika tidak menggunakan Git, bisa rename file `.env.example` menjadi `.env`
5. Pada terminal `php artisan key:generate`
6. Buat **database pada mysql** untuk aplikasi ini
7. **Setting database** pada file `.env`
8. `php artisan db:seed --class=ProductsSeeder`
9. `php artisan serve`
10. Selesai
