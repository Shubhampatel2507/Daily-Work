FROM ubuntu
RUN  apt-get update \
  && DEBIAN_FRONTEND=noninteractive apt-get install -y \
    apache2 \
    mysql-server \
    php7.0 

# Expose apache.
EXPOSE 80
EXPOSE 8080