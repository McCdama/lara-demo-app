# Laravel-Demo-App


## Getting started

- [ ] Open Terminal Terminal
```
git clone git@github.com:McCdama/lara-demo-app.git
cd .\lara-demo-app

npm install
```
__Run__
```
npm run dev

```

- [ ] Open **another** Terminal in the root directory

Enter your __*Spark Credentials*__
```
composer config http-basic.spark.laravel.com your-email@example.com your-api-token
```

[Please refer to Spark offical site for detailed information](https://spark.laravel.com/docs/4.x/installation.html)

```
composer update
php artisan migrate
php artisan key:generate
```
__Run__

```
php artisan serve
```
