PHP 5.6 / FPM container
-----------------------------------
Debian Jessie PHP 5.6 / FPM container from PHPDocker.io projects.

Smaller in size than PHP's official container (200MB vs 460MB) plus you don't need to install any build dependencies let alone compile anything, Debian Jessie already ships binaries for the vast majority, if not all, of PHP extensions.

PHP extensions:
**php5-apcu,
php5-curl,
php5-gd,
php5-imagick,
php5-intl,
php5-json,
php5-mcrypt,
php5-mysqlnd,
php5-readline**

Extras:
**Composer**

Note on logging: configure your application to stream logs into *php://stdout*. That's it.
