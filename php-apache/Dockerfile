FROM php:8.0-apache
RUN docker-php-ext-install mysqli -y
RUN docker-php-ext-enable mysqli -y
RUN apt-get update && apt-get upgrade -y
COPY ../Simple-PHP-blog/ /var/www/html