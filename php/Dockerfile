FROM php:8.1-fpm
COPY php.ini /usr/local/etc/php/
RUN docker-php-ext-install mysqli pdo_mysql exif
# composer
COPY --from=composer /usr/bin/composer /usr/bin/composer