FROM php:8.0.24-fpm-alpine3.15
RUN apk add --no-cache libzip-dev icu-dev
RUN docker-php-ext-install mysqli pdo_mysql bcmath zip intl opcache
