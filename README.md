# php-5.6.13-win32-VC12
PHP 5.6.13 Windows binaries including all standand extensions present in original PHP distribution compiled using **Visual Studio 2013**. The purpose of this package is to be able to load `php_v8` extension becase it's not able to compile V8 using older versions of Visual Studio.

## Steps to install
* Unpack
* Copy and rename `php.ini-development` to `php.ini`
* Optionally download additional extensions [here](https://github.com/maryo/php-5.5-windows-extensions), compiled extensions from original PHP distribution won't work since they're compiled using an older version of Visual Studio
* Update Your Path system environment variable

![dialog](http://static.xpertdeveloper.com/uploads/2011/09/environment_variable_2.jpg)
