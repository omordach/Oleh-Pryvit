[![Build Status](https://travis-ci.com/omordach/Oleh-Pryvit.svg?branch=master)](https://travis-ci.com/omordach/Oleh-Pryvit) 
![StyleCI](https://github.styleci.io/repos/240292474/shield?branch=master)
# Oleh/Pryvit
## Installation
### Install package
```
composer require oleh/pryvit
```
## Operating
### Create index.php
```
<?php

require 'vendor/autoload.php';

echo (new \Oleh\Pryvit\WordFactory)->hello() . PHP_EOL;
```
### Run 
```
php index.php
```

### Result
```
$ php index.php
Привіт!
```

## Changelog
https://github.com/omordach/Oleh-Pryvit/releases

## Packagist
https://packagist.org/packages/oleh/pryvit

## Licence
Licence: MIT License
