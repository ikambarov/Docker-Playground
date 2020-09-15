FROM ubuntu
MAINTAINER Islam Kambarov (ikambarov@yahoo.com)
RUN apt-get update -y && apt-get install -y nginx
EXPOSE 80
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
