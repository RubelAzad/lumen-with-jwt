# lumen-with-jwt

# Installation

1. Clone this repo

```
git clone https://github.com/RubelAzad/lumen-with-jwt.git
```

2. Install composer packages

```
cd lumen-with-jwt
$ composer install
```

3. Create and setup .env file

```
make a copy of .env.example
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
$ php artisan jwt:secret
```

4. Migrate and insert records with MSSQL

[![Install ODBC Drive]](https://learn.microsoft.com/en-us/sql/connect/odbc/download-odbc-driver-for-sql-server?view=sql-server-ver16)

```
$ php artisan migrate
```

#extra package use this system

1. Flipbox Install For Command

```
$ composer require flipbox/lumen-generator

```

[![Flipbox Documentation Link]](https://github.com/flipboxstudio/lumen-generator)

```

2. Install JWT Auth

```

$ composer require tymon/jwt-auth

```

[JWT auth Documentation link](https://medium.com/rajtechnologies/laravel-lumen-authentication-jwt-auth-e6b175beaf89)




