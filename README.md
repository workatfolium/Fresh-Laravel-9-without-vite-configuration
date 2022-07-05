## Installation

*Select (with_breeze) From Branch Dropdown & Download the repository.(Don't Clone the repository just download it in zip.)*

*After Downloading zip Go to Fresh-Laravel-9-without-vite-configuration-with_breeze folder and open terminal then follow below steps.*

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

*Install NPM Dependencies:*
```
npm install
```

*Build Assets:*
```
npm run dev
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

*You Will Find The Running Laravel(With Laravel Breeze Authentication Added) App Without The Latest Vite configuration Which has been added in latest laravel v9.2.0.*