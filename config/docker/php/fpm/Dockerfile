FROM php:5.6-fpm

RUN apt-get update && apt-get install -y git file wget libicu-dev libmcrypt-dev libpq-dev libzmq3 libzmq3-dev

RUN docker-php-ext-install mysql pdo pdo_mysql mbstring intl mcrypt pdo_pgsql
