# Basic Hello World script for PHP Composer #

A package which returns "Hello World"

## Usage ##

```bash
$ composer require rivsen/hello-world
$ touch index.php
```

```php
<?php
require_once "vendor/autoload.php";

$hello = new Funami\Hello\Hello();
echo $hello->hello();
```

```bash
$ php test.php
```

It will print "Hello World!" then exit.
