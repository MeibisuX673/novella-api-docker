FROM php:8.0.3-apache

RUN docker-php-ext-install \
  pdo_mysql \
  && a2enmod \
  rewrite