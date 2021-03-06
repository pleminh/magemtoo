Magemtoo - Module Creator for Magento 2
====================

Description:
----------

Magento 2 Module helps to generate a module prototype based on the vendor name and the module name.

 - version: 0.1

Requirements:
----------
 - PHP 5.5.x >
 - Twig
 - Magento 2.x >

Installation
------------

### Step 1: Download the bundle


Open a command console, enter your project directory and execute the
following command to download the latest stable version of this bundle:

```bash
$ composer require pleminh/magemtoo
```

This command requires you to have Composer installed globally, as explained
in the [installation chapter](https://getcomposer.org/doc/00-intro.md)
of the Composer documentation.

### Step 2: Enable the Bundle

Then, enable the bundle , execute the following command:

```bash
$ php bin/magento setup:upgrade
```


Usage
-----

### Commands

## Usage

```
$ php bin/magento magemtoo:generate:module --help

Usage:
 magemtoo:generate:module [--vendor-name="..."] [--module-name="..."]

Options:
 --vendor-name         The vendor name - used for namespace - eg : Magemtoo
 --module-name         The module name - word that describes what the module does. eg : Swifter
 --help (-h)           Display this help message
 --quiet (-q)          Do not output any message
 --verbose (-v|vv|vvv) Increase the verbosity of messages: 1 for normal output, 2 for more verbose output and 3 for debug
 --version (-V)        Display this application version
 --ansi                Force ANSI output
 --no-ansi             Disable ANSI output
 --no-interaction (-n) Do not ask any interactive question
```


#### magemtoo:generate:module

This command will generate a base skeleton module prototype based on the vendor name and the module name.

```bash
$ php bin/magento magemtoo:generate:module
```


Roadmap
----------
- Create theme prototype 
- Create CRUD system prototype based on the structure of [pleminh/magento2-blog-product](https://github.com/pleminh/magento2-blog-product)
