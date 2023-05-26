
FROM nginx:1.18.0-alpine


COPY ./dist/spa  /usr/share/nginx/html

COPY ./nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]



