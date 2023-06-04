FROM nginx:1.24.0

COPY index.html /usr/share/nginx/html/index.html

COPY nginx.conf /etc/nginx/nginx.conf

CMD ["nginx" "-g" "daemon off;"]