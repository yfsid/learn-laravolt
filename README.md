<p align="center"><a href="https://laravolt.dev" target="_blank"><img src="https://d33wubrfki0l68.cloudfront.net/14ca1a42334732460cb2f1b2d6f3d81f80b07613/121e8/assets/img/logo.png" width="100"></a></p>

## About Laravolt

https://laravolt.dev/

## History

1. Install Laravel v9.24.0 in PHP v8.1.9
1. Install Laravolt v5.2

## Server Requirements

1. PHP 8.x
1. Composer 2
1. PostgreSQL (recommended) or MariaDB

## Local Setup

1. Clone repository
1. Jalankan `composer install`
1. Salin .env.example ke .env
1. Sesuaikan konfigurasi database dan lain-lain
1. Jalankan 'php artisan key:generate'
1. Jalankan 'php artisan migrate:fresh --seed'
1. Jalankan 'php artisan storage:link'
1. Jalankan 'php artisan vendor:publish --tag=laravolt-assets'
1. Pastikan folder-folder berikut _writeable_:
    1. bootstrap/cache
    1. storage
1. Jalankan 'php artisan serve'

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
