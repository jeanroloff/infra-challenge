## About project infra-challenge

This is a api example project for a technical test the application infrastructure.

### Setup

1. After clone project, run install dependencies
```shell
composer install
```

2. The projetct requires MySQL installed, configure the credentials in .env file
```shell
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

3. Run migrations with seeders
```shell
php artisan migrate --seed
```

4. Access the example endpoint
```shell
curl http://127.0.0.1:8000/api/v1/products
```


