FROM nginx:latest

COPY ./app /usr/share/nginx/html
COPY ./compose/production/nginx/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]