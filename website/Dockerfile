FROM php:7.0-apache
# COPY config/php.ini /usr/local/etc/php/
RUN docker-php-ext-install pdo pdo_mysql mysqli
COPY src/ /var/www/html
EXPOSE 80