FROM composer:1.9.3 AS composer
COPY --from=composer /usr/bin/composer /usr/bin/composer
WORKDIR /app
COPY . .
RUN composer install