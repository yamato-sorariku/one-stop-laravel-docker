FROM php:7.2.12-fpm-alpine3.8

RUN docker-php-ext-install pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php -- --version=1.8.0 && \
    mv composer.phar /usr/local/bin/composer