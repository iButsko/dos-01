
# Dockefile to build Docker Image of Apache WebServer on Ubuntu
#
# Made by Ivan Butsko
# Using 16.04 because have problem with 20.04 

FROM ubuntu:16.04

RUN apt-get -y update
RUN apt-get -y install apache2

RUN echo 'I am trying to create web page througth docker' > /var/www/html/index.html


CMD ["/usr/sbin/apache2ctl", "-D","FOREGROUND"]
EXPOSE 80

