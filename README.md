# Ping CRM React + Laravel 7

A demo application to illustrate how [Inertia.js](https://inertiajs.com/) works with [Laravel](https://laravel.com/) and [React](https://reactjs.org/).

> This is a port of the original [Ping CRM](https://github.com/inertiajs/pingcrm) written in Laravel and Vue.

![](https://raw.githubusercontent.com/nagibmahfuj/pingcrm-react-laravel/master/screenshot.png)

## Installation

Clone the repo locally:

```sh
git clone https://github.com/nagibmahfuj/pingcrm-react-laravel.git
cd pingcrm-react-laravel
```

Install PHP dependencies:

```sh
composer install
```

Install NPM dependencies:

```sh
npm install
```

Build assets:

```sh
npm run dev
```

Setup configuration:

```sh
cp .env.example .env
```

Generate application key:

```sh
php artisan key:generate
```

Create an SQLite database. You can also use another database (MySQL, Postgres), simply update your configuration accordingly.

```sh
touch database/database.sqlite
```

Run database migrations:

```sh
php artisan migrate
```

Run database seeder:

```sh
php artisan db:seed
```

Run artisan server:

```sh
php artisan serve
```

You're ready to go! [Visit Ping CRM](http://127.0.0.1:8000/) in your browser, and login with:

-   **Username:** johndoe@example.com
-   **Password:** secret

## Running tests

To run the Ping CRM tests, run:

```
phpunit
```

## Credits

-   Cloned and Updated - Actually he made it for Laravel 6 (https://github.com/landish/pingcrm-react) by Lado Lomidze (@landish)
-   Original work by Jonathan Reinink (@reinink) and contributors
-   Port to Ruby on Rails by Georg Ledermann (@ledermann)
-   Port to React by Lado Lomidze (@landish)
