# Laravel Provider for Railt

<p align="center">
    <a href="https://travis-ci.org/railt/laravel-provider"><img src="https://travis-ci.org/railt/laravel-provider.svg?branch=master&" alt="Travis CI" /></a>
    <a href="https://scrutinizer-ci.com/g/railt/laravel-provider/?branch=master"><img src="https://scrutinizer-ci.com/g/railt/laravel-provider/badges/quality-score.png?b=master&" alt="Scrutinizer CI" /></a>
    <a href="https://scrutinizer-ci.com/g/railt/laravel-provider/?branch=master"><img src="https://scrutinizer-ci.com/g/railt/laravel-provider/badges/coverage.png?b=master&" alt="Code coverage" /></a>
    <a href="https://packagist.org/packages/railt/laravel-provider"><img src="https://poser.pugx.org/railt/laravel-provider/version?" alt="Latest Stable Version"></a>
    <a href="https://packagist.org/packages/railt/laravel-provider"><img src="https://poser.pugx.org/railt/laravel-provider/v/unstable?" alt="Latest Unstable Version"></a>
    <a href="https://raw.githubusercontent.com/railt/laravel-provider/master/LICENSE"><img src="https://poser.pugx.org/railt/laravel-provider/license?" alt="License MIT"></a>
</p>

## About

The Laravel Framework Service Provider for Railt.

## Installation

### Laravel 5.5+

> Make sure that you are using at least PHP 7.1

- `composer require railt/laravel-provider`
- `php artisan vendor:publish --tag=railt`

### Laravel 5.4 or less

- `composer require railt/laravel-provider`
- Add the service provider to your `app/config/app.php` file:
```php
'providers' => [
    // ...
    Railt\LaravelProvider\RailtServiceProvider::class,
]
```

- `php artisan vendor:publish --tag=railt`
