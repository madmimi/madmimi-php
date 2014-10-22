# MadMimi for PHP

### Install with Composer

Simply add a dependency on `hasandz/madmimi-php` to your project's `composer.json` file if you use [Composer](http://getcomposer.org/) to manage the dependencies of your project. Here is a minimal example of a `composer.json` file that just defines a dependency:

    {
        "require": {
            "hasandz/madmimi-php": "dev-master"
        }
    }

## Notes on basic usage:
$mimi = new MadMimi('username', 'api_key');

$mimi->Promotions();

$mimi->Lists();

...and etc. For more detailed examples, see the Examples directory.

General Mad Mimi API documentation can be found at the [Mad Mimi developer's wiki.](http://madmimi.com/developer)

## Contributors
gorilla3d
lehresman

## License
(C) Copyright 2010 Mad Mimi, LLC <support@madmimi.com>
Released under the MIT License.
