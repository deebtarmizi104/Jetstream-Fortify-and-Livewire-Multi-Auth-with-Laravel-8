# Jetstream Fortify and Livewire Multi Auth with Laravel 8.x

## Covering:
- Basic authentication setup
- Admin Login Panel and Data Seedings

## Make use of:
- LARAVEL 8.x
- myphpadmin
- xampp 8.0.8
- php 8.0.8
- bootstrap 5
- composer 2.1.3
- dbdesigner.net

## Footnotes
* install composer
* unlinked composer
* create laravel project - composer create-project --prefer-dist laravel/laravel projectname
* update composer - composer require laravel/ui "^3.0" --dev
* create jetstream routing - composer require laravel/jetstream
* livewire installation - php artisan jetstream:install livewire
* nodejs installation - npm install && npm run dev
* enabling storage - php artisan storage:link
* install default authentication - php artisan ui vue --auth
* create Model - php artisan make:model model_name -m
* create seeder - php artisan make:seed seed_name
* migrate created table - php artisan migrate
* seed created data - php artisan db:seed
* create controller - php artisan make:controller controller_name
* create middleware - php artisan make:middleware middleware_name
* listing route - php artican r:l OR php artisan route:list
* install laravel helpers - composer require laravel/helpers
* image intervention installation - composer equire intervention/image
  - http://image.intervention.io/getting_started/installation
  - enable extension=gd in php.ini
* email verification feature enabler - Features::emailVerification() in config -> fortify.php
* 419 error - check csrf tokens

