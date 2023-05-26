
FROM nginx:1.18.0-alpine

WORKDIR /app

COPY /app/dist/spa /usr/share/nginx/html

COPY /app/nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]


