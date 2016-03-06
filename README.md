# php-5.6.13-win32-VC12
PHP 5.6.13 Windows binaries including all standand extensions present in original PHP distribution compiled using :exclamation:**Visual Studio 2013**:exclamation:.
The purpose of this package is to be able to load `php_v8` extension because VC12 is a minimum version you can compile V8 on windows with.

## Steps to install
(the same as using zip package from the original PHP windows distribution)
* Unpack
* Copy and rename `php.ini-development` to `php.ini`
* Optionally download additional extensions from [here](https://github.com/maryo/php-5.6-extensions-win32-VC12)
* :exclamation: Compiled extensions from original PHP distribution won't work:exclamation: since they're compiled using an older version of Visual Studio
* Update Your Path system environment variable

![dialog](http://static.xpertdeveloper.com/uploads/2011/09/environment_variable_2.jpg)
