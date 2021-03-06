# Symfony Micro Framework Bundle

A replacement of the official FrameworkBundle allowing Symfony to be used as a
micro-framework which follows the "add what you need" philosophy.

## Installation

First install it using [Composer](https://getcomposer.org/download):

    composer require gnugat/micro-framework-bundle:^0.1

Then enable it in your application's kernel (e.g. `app/AppKernel.php`):

    new Gnugat\MicroFrameworkBundle\GnugatMicroFrameworkBundle()

## Features

* compatible with third party bundles
* better performance than FrameworkBundle (faster autoloading, lighter DIC)

## Want to know more?

You can see the current and past versions using one of the following:

* the `git tag` command
* the [releases page on Github](https://github.com/gnugat/micro-framework-bundle/releases)
* the file listing the [changes between versions](CHANGELOG.md)

And finally some meta documentation:

* [copyright and MIT license](LICENSE)
* [versioning and branching models](VERSIONING.md)
* [contribution instructions](CONTRIBUTING.md)
