FROM php:7-apache
 
# PHP extensions
RUN apt-get update && apt-get install -y \
        libfreetype6-dev \
        libjpeg62-turbo-dev \
        libmcrypt-dev \
        libpng-dev \

RUN docker-php-ext-install pdo_mysql

