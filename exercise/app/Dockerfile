FROM nginx:latest

RUN apt update && apt install nano dnsutils -y

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80