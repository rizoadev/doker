FROM ubuntu

# install nginx
RUN apt update -y; apt install nginx -y

# golek dewe docs e yo

WORKDIR /home 
COPY ./config/nginx /etc/nginx
COPY ./html /home/html

CMD nginx -g 'daemon off;'