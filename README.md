### How to install restfull api with lumen
##### 1. Clone this project

```bash
$ git clone https://github.com/ahmadpato/api-car-rental 
```


##### 2. Install lumen

```bash
$ composer create-project laravel/lumen api-car-rental --prefer-dist
```

##### 3. Setup database in .env

```bash
$ DB_DATABASE=
DB_USERNAME=youruername
DB_PASSWORD=yourpassword(if any)
```

##### 4. Migration with run this function
```bash
$ php artisan migrate

```

##### 5. Run this project
```bash
$ php -S localhost:8000 -t ./public
```

##### 6. Open your postman
example : http://localhost:8000/api-car-rental/
