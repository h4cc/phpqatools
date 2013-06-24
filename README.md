h4cc/phpqatools
==========

This is a composer meta package for installing PHP Quality Assurance Tools with only one dependency.
Only stable packages are used, to keep the configuration easy and secure.

Included in this package are:
- PHPUnit
- PHP-Invoker
- DbUnit
- PHP_Depend
- PHPMD
- PHP_CodeSniffer
- Apigen
- Sami


# Usage

The installed tools are available in vendor/bin/ and can be started like this:

  php vendor/bin/phpmd
  

# Installation

To use this package, add it as as "dev" dependency with this command:

  php composer.phar require h4cc/phpqatools --dev

Or modify your composer.json as followed:

  require-dev: {
    "h4cc/phpqatools": "*"
  }

More info about development dependencies: http://getcomposer.org/doc/04-schema.md#require-dev


# Todo

A phing buildfile may be included someday.
I hope some more tools get available in stable versions, so i can add them here.
