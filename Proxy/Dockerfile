FROM ubuntu:latest
RUN apt-get update && apt-get install -y nginx git

COPY default /etc/nginx/sites-available/default


CMD ["nginx", "-g", "daemon off;"]