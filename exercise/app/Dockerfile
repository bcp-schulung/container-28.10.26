FROM alpine:latest

RUN apk add --no-cache nginx \
    && mkdir -p /run/nginx \
    && printf '%s\n' \
        'server {' \
        '    listen 80;' \
        '    server_name _;' \
        '    root /var/www/html;' \
        '    index index.html;' \
        '}' > /etc/nginx/http.d/default.conf

COPY index.html /var/www/html/index.html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]