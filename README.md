# php56-fpm

PHP 5.6 / FPM container
-----------------------------------
Debian Jessie PHP 5.6 / FPM container from PHPDocker.io projects.

Smaller in size than PHP's official container (200MB vs 460MB) plus you don't need to install any build dependencies let alone compile anything, Debian Jessie already ships binaries for the vast majority, if not all, of PHP extensions.

Extras:
**Composer**

Note on logging: configure your application to stream logs into *php://stdout*. That's it.
