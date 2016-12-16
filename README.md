# PHP-FPM 7.1.0 in Docker

It is been adopted and updated from [official version](https://hub.docker.com/_/php/) to work under Ubuntu 16.04. This is a standalone version and can be combined using a `docker-compose.yml` with a webserver.
```
 $ docker build --tag=php-fpm:7.1.0 --force-rm --no-cache .
```
