FROM php:8.1-fpm
ENV HOSTNAME masonajalah
COPY . /app
WORKDIR /app
RUN docker-php-ext-install pdo_mysql
