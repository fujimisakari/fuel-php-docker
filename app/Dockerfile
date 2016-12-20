FROM php:5.6.29-fpm

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
ENV DOCKER true

RUN rm -rf /usr/local/etc/php-fpm.d
RUN mkdir /var/run/php-fpm

RUN apt-get update
RUN apt-get install -y mysql-client vim net-tools telnet curl
