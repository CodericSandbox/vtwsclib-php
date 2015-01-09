# vtwsclib-php

Vtiger Web Services PHP Client Library

## Installing via Composer

The recommended way to install **vtwsclib-php** is through [Composer](https://getcomposer.org/).

    # Install Composer
    curl -sS https://getcomposer.org/installer | php

Next, run the Composer command to install the latest stable version of Guzzle:

    composer require salaros/vtwsclib-php

..or edit your composer.json file manually by adding:

    {
        "require": {
            "salaros/vtwsclib-php": "dev-master"
        }
    }

After installing, you need to require Composer's autoloader:

    require 'vendor/autoload.php';
