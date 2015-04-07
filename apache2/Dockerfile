# The Apache HTTP Server
#
# VERSION	2.0

FROM alpine:latest

MAINTAINER Thomas Duesing <TFDuesing@gmail.com>

RUN /sbin/apk add --update apache2 && rm -rf /var/cache/apk/*

EXPOSE 80

CMD ["/usr/sbin/apachectl", "-D", "FOREGROUND"]
