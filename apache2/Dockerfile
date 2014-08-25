# apache2
#
# VERSION	1.0

FROM ubuntu:14.04.1

MAINTAINER Thomas Duesing <TFDuesing@gmail.com>

ENV DEBIAN_FRONTEND noninteractive

RUN ["/usr/bin/apt-get", "-qq", "update"]
RUN ["/usr/bin/apt-get", "-qq", "install", "apache2"]

EXPOSE 80

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
