# login & authentication with laravel

Login and register system in laravel using Jetstream

## Documentation

https://jetstream.laravel.com/2.x/introduction.html

## Methods

1. ```npm install```
2. Config DB_DATABASE, DB_USERNAME and DB_PASSWORD in .env file (use MySQL database)
3. Modify the file ./app/Providers/AppServiceProvider.php
    - Add 
    ```use Illuminate\Support\Facades\Schema;```
    - Add
    ```Schema::defaultstringLength(191);``` into boot function
4. ```php artisan serve ```
5. ```composer require laravel/jetstream```
6. ```php artisan jetstream:install livewire```
7. ```npm run dev```
8. ```php artisan migrate```
9. ```php artisan serve```
