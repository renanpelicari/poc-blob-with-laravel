
## POC - Personal Blog under Laravel

A simple personal blog using Laravel Framework.

## Tech Stack
* [Laravel 5.5](https://laravel.com/docs/5.5/releases);
* [PHP 7](http://www.php.net/);
* [PostgreSQL under Docker](https://hub.docker.com/_/postgres/);

## Installing Laravel

* First of all you need to install laravel following this guide [Laravel Installation](https://laravel.com/docs/5.5/installation);
* After this you need to config database, in this POC we will use the Postgres at Docker. The next chapter I will explain step by step;

## DB and Docker

* [Install docker](https://hub.docker.com/_/postgres/);
* Start docker with the follow command: `docker run --name blog-laravel -e POSTGRES_PASSWORD=larapass123 -d postgres`
* Execute migration command under laravel project folder: `php artisan migrate`

## Author
Renan Peliçari Rodrigues

renanpelicari@gmail.com

https://www.linkedin.com/in/renanpelicari/

https://github.com/renanpelicari
