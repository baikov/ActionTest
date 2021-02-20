FROM nginx:latest

COPY ./app /usr/share/nginx/html
COPY ./compose/local/nginx/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

RUN echo "${LOCAL_VAR}"

CMD ["nginx", "-g", "daemon off;"]