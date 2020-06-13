FROM ubuntu:18.04
MAINTAINER Dennis Chukwunta <chuksmcdennis@yahoo.com>

RUN apt-get update -y
FROM php:7.2-apache
RUN apt-get update && apt-get install -y

RUN docker-php-ext-install mysqli pdo_mysql

RUN rm -rf /var/www/html/*
ADD . /var/www/html/


WORKDIR /var/www/html/
