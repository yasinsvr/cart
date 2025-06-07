# Laravel Shopping Cart
A Shopping Cart Implementation for Laravel Framework
### **It's for viersions 10 & 11 & 12**

## INSTALLATION

Install the package through [Composer](http://getcomposer.org/).

```php
composer require yasinsvr/cart
```

## CONFIGURATION

1. Open config/app.php and add this line to your Service Providers Array.

```php
YasinSVR\Cart\CartServiceProvider::class
```

2. Open config/app.php and add this line to your Aliases

```php
  'Cart' => YasinSVR\Cart\Facades\CartFacade::class
```

3. Optional configuration file (useful if you plan to have full control)

```php
php artisan vendor:publish --provider="YasinSVR\Cart\CartServiceProvider" --tag="config"
```

**Enjoy from laravel shopping cart :)**


