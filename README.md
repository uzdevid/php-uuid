PHP UUID
========
UUID Generator

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist uzdevid/php-uuid "1.0"
```

```
composer require --prefer-dist uzdevid/php-uuid "1.0"
```

or add

```
"uzdevid/php-uuid": "1.0"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php $uuid = \uzdevid\uuid\UUID::generate(); ?>
```