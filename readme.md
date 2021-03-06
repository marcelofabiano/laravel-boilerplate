<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Laravel 5.8 Boilerplate

Laravel 5.8 Boilerplate by Florian B.

## Features - Changes from the official Laravel project

* Authentication system (Using the `artisan make:auth` command)
  * Seeder for a default user (email: `admin@local.dev`, password: `admin`)
* Third-party libraries for more efficient development
    * IDE Helper (With the `barryvdh/laravel-ide-helper` library)
    * Laravel Debugbar (With the `barryvdh/laravel-debugbar` library)
    * Laravel N+1 Query Detector (With the `beyondcode/laravel-query-detector` library)
* French translations (Based on the `caouecs/laravel-lang` library)
* Timezone set on `Europe/Paris`
* Configuration `defaultStringLength` set to `191` (for possible compatibility issues)
* Remove default routes for `api`, `channels`, and `console`
* Add the `.idea` folder to the `.gitignore` file

## System Requirements

* PHP >= 7.1.3
* OpenSSL PHP Extension
* PDO PHP Extension
* Mbstring PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension
* Ctype PHP Extension
* JSON PHP Extension
* BCMath PHP Extension

## License

The Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).
