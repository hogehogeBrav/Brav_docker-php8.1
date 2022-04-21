FROM php:8.1-fpm
COPY php.ini /usr/local/etc/php/
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install exif