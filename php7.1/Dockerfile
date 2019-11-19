FROM  wordpress:php7.1

ENV PHP_OPCACHE_VALIDATE_TIMESTAMPS="0"

ADD opcache.ini "$PHP_INI_DIR/conf.d/opcache.ini"

RUN docker-php-ext-install opcache
