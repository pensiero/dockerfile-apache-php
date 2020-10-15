## dockerfile-apache-php

Docker image with Apache and PHP7

### How to use it
Use as image tag `pensiero/apache-php`.

### Where to mount volumes
While running, Apache is gonna look by default at the content of the folder `/var/www`.
Use that as mount point for your volumes.

### Branches for different Docker image tags

The `master` branch is always associated with the `latest` tag of the Docker image.

This repository also comes with different feature branches for different Docker image tags.
For example, the branch: `feature/php71` is associated with the tag `php7.1`.

### Available PHP versions
Check out all the available tags here on [Docker Hub](https://hub.docker.com/repository/docker/pensiero/apache-php/tags).

If you wanna use different php version, you can leverage the following images
- `PHP 5.6` --> `pensiero/apache-php:php5.6`
- `PHP 7.0` --> `pensiero/apache-php:php7.0` 
- `PHP 7.1` --> `pensiero/apache-php:php7.1`
- `PHP 7.2` --> `pensiero/apache-php:php7.2`
- `PHP 7.4` --> `pensiero/apache-php:php7.4`
