
# African Payment Solutions Assessment project



## Authors

- [Tlholiso W. Tukisi](twtukisi@gmail.com)


## Tech Stack


**RDBMS:** [MySQL 8](https://dev.mysql.com/downloads/mysql/)

**Language:** [PHP 7.4](https://www.php.net/downloads.php)

**Framework:** [Laravel 8](https://laravel.com/docs/8.x/installation)


## Prerequesite

**Edit .env file**

From the root directory of the project, open the .env file and edit the following variables to accomodate your database setup on your environment:

```bash
DB_CONNECTION=mysql
DB_HOST=
DB_PORT=
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```
Then run the migrations and seeders to create and populate your BD tables with data
```bash
php artisan migrate

php artisan db:seed --class=UserSeeder

```


Incase you experiance challenges with Migrations, you can refere to [Laravel Migrations Ducumenations](https://laravel.com/docs/8.x/migrations)


