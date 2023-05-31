
FROM nginx:1.18.0-alpine
COPY ./dist/spa  /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]