# SoftwareEngineering_Project
This application was made in order to finish my Software Engineering Course in a group of 4.
## How to use
In order to run the application, you need to have composer installed and then run
```
composer install
```
You need to set the database name, application name in the .env by copying the .env.example.
After you create the .env, run 
```
php artisan key:generate
```
and
```
php artisan migrate:fresh --seed
```
