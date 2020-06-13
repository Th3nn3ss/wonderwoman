FROM ubuntu:18.04
MAINTAINER Dennis Chukwunta <chuksmcdennis@yahoo.com>

RUN apt-get update -y
FROM php:7.2-apache
RUN apt-get update && apt-get install -y
COPY /main/ /var/www/html/
COPY php.ini /usr/local/lib/
