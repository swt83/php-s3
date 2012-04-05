# Amazon S3 for LaravelPHP #

This is a simple Laravel wrapper for using Donovan Schönknecht's Amazon S3 class.

## Installation & Usage ##

Install the bundle, setup the config file, and then check [Donovan Schönknecht's Github Page](https://github.com/tpyo/amazon-s3-php-class) for the available methods.

Just call the methods direct, don't worry about the ``new S3()`` or ``S3::setAuth()`` class prep methods, those will automatically be handled by the wrapper.

## Upkeep ##

To update the class w/ any new revisions by Donovan, replace ``vendors/s3.php`` with the latest file and perform the following steps:

* Add ``namespace Amazon;`` to the top of the file.
* Add ``\`` to all ``stdClass`` and ``Exception`` class calls.
* Copy the class constants into the ``libraries/s3.php`` file.