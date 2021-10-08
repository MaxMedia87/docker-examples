FROM php:7.4-fpm-alpine

# $PHP_INI_DIR переменная окружения доступная из образа или указать полный путь
# $PHP_INI_DIR = /usr/local/etc/php

RUN mv $PHP_INI_DIR/php.ini-development $PHP_INI_DIR/php.ini

COPY conf.d /usr/local/etc/php/conf.d

WORKDIR /app
