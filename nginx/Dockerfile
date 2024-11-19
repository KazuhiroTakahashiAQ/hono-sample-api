FROM --platform=linux/amd64 nginx:latest

# COPY nginx.conf /etc/nginx/nginx.conf
COPY nginx.conf /etc/nginx/conf.d/nginx.conf

COPY index.html /usr/share/nginx/html/index.html

EXPOSE 80
