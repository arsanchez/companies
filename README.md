# Laravel Project README

This is a Laravel project repository. Follow the steps below to set up and run the project on your local development environment.

## Prerequisites

Before you begin, make sure you have the following software installed on your system:

- [Git](https://git-scm.com/)
- [Composer](https://getcomposer.org/)
- [PHP](https://www.php.net/) (with required extensions for Laravel)
- [Node.js](https://nodejs.org/) (optional, for frontend assets)

## Getting Started

In order to setup the app please execute the following commands in the app root

Laravel Setup

`composer install`

`cp .env.example .env`

After copying the env file please fill the db config 

`DB_CONNECTION=mysql`

`DB_HOST=127.0.0.1`

`DB_PORT=3306`

`DB_DATABASE=laravel`

`DB_USERNAME=root`

`DB_PASSWORD=`

`php artisan key:generate`

`php artisan migrate`

`php artisan db:seed`


Vue setup

`npm i`

`npm run dev`


