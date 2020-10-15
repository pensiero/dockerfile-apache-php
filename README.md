### dockerfile-apache-php

Docker image with Apache and PHP7

### How to use it
While running, Apache is gonna look by default at the content of the folder `/var/www`.
Use that as mount point for your volumes.

### Branches for different Docker image tags

The `master` branch is always associated to the `latest` tag of the Docker image.

This repository also comes with different feature branches for different Docker image tags.

For example, the branch: `feature/php71` is associated with the tag `php7.1`.

### Available PHP versions
- `php5.6` --> `pensiero/apache-php:php5.6`
- `php7.0` --> `pensiero/apache-php:php7.0` 
- `php7.1` --> `pensiero/apache-php:php7.1`
- `php7.2` --> `pensiero/apache-php:php7.2`
