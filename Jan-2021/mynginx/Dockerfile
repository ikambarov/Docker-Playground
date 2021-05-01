FROM ubuntu
MAINTAINER Islam Kambarov (ikambarov@yahoo.com)
RUN apt-get update
RUN apt-get install -y nginx
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
