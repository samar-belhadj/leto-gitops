#####################################
## Set NGINX image as base image
#####################################
FROM nginx:1.18.0-alpine

##########################################################
## COPY APP FROM BUILD STAGE
##########################################################

COPY ./dist /usr/share/nginx/html
COPY ./nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]




