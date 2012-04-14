# Amazon S3 for LaravelPHP #

This is a simple wrapper for using [Donovan Schönknecht's Amazon S3 class](https://github.com/tpyo/amazon-s3-php-class).

## Install ##

Copy the config file to ``application/config/s3.php`` and input the proper information.

## Usage ##

Check [here](https://github.com/tpyo/amazon-s3-php-class) for a list of all available methods.  Don't worry about authentication methods, the wrapper will handle that for you.

```php
S3::put_object($string, $bucket, $path, S3::ACL_PUBLIC_READ);
```