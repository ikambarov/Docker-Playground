FROM ubuntu
LABEL maintainer="Islam Kambarov (ikambarov@yahoo.com)"
RUN apt-get update && apt-get install -y nginx
EXPOSE 80
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]

