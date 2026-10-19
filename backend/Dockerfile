FROM php:8.2-fpm
WORKDIR /var/www/html
RUN apt-get update && apt-get install -y libpng-dev libjpeg-dev libfreetype6-dev zip git
RUN docker-php-ext-install pdo_mysql gd
