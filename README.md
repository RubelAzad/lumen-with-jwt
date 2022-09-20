# lumen-with-jwt

# Installation
Clone this repo
git clone
Install composer packages
cd lumen-rest-api-jwt-auth
$ composer install
Create and setup .env file
make a copy of .env.example
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
$ php artisan jwt:secret
Migrate and insert records
$ php artisan migrate

