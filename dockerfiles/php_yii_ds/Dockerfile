FROM php:5.6-apache

RUN docker-php-ext-install pdo pdo_mysql bcmath

RUN a2enmod rewrite

COPY 000-default.conf /etc/apache2/sites-available/
COPY php.ini /usr/local/etc/php/

