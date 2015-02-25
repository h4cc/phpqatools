h4cc/phpqatools [![Build Status](https://travis-ci.org/h4cc/phpqatools.png?branch=master)](https://travis-ci.org/h4cc/phpqatools)
==========

This is a composer meta package for installing PHP Quality Assurance Tools with only one dependency.
Only stable packages are used, to keep the configuration easy and secure.

Included in this package are:
- PHPUnit
- PHP-Invoker
- DbUnit
- PHPLOC
- PHPCPD
- PHP_Depend
- PHPMD
- PHP_CodeSniffer
- Fabien Potencier/PHP Coding Standards Fixer
- Sensiolabs/Security-Checker
- Behat
- Codeception


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


# Versioning

This package will be updated, when newer or other stable packages become available. Fell free to suggest tools if they are missing.

To avoid problems you may not use composer version constraints like this "~1.1". Such a constraint will always upgrade to the newest "1.\*" version which might break your toolchain.
In such a case, simply stick to a minor-version like "1.2.\*".


# Todo

A phing buildfile may be included someday.
I hope some more tools get available in stable versions, so i can add them here.
