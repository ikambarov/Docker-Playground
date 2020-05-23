FROM ubuntu:xenial
LABEL maintainer="ikambarov@evolvecyber.com"
RUN apt-get update && apt-get install apache2 -y
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

