# VIN Validator

This module does simple VIN validation. It checks for proper length, characters, and a valid check digit.

## Usage

```shell
composer require woodongwong/vin-validate
```

```php
require_once __DIR__ . '/vendor/autoload.php';

var_dump(\WoodongWong\VinValidate\VinValidator::verify('11111111111111111'));  // true
```
