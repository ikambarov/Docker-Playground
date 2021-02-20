FROM ubuntu:xenial
LABEL maintainer="ikambarov@yahoo.com"
RUN apt-get update && apt-get install nginx -y 
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
