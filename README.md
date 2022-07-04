## Installation

*Download or clone the repository in your system.*
```
git clone https://github.com/workatfolium/Fresh-Laravel-9-without-vite-configuration.git
```

*Go to Fresh-Laravel-9-without-vite-configuration folder and open terminal then follow below steps.*

*Install or Update Composer:*
```
composer install
```

*Make a copy of .env.example file to .env:*
```
cp .env.example .env
```

*Set the database credentials:*

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=yourdb
DB_USERNAME=yourdbuser
DB_PASSWORD=yourdbpassword
```

*Then Generate Application Key:*

```
php artisan key:generate
```

*Migrate database:*
```
php artisan migrate
```

*Clear cache by below command:*
```
php artisan optimize
```

*Start Server:*
```
php artisan serve
```

*Then Visit:*

http://127.0.0.1:8000/

*You Will Find The Running Laravel App Without The Latest Vite configuration Which has been added in latest laravel v9.2.0.*