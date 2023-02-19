# base image
FROM nginx:alpine

# copy static files to nginx html directory
COPY . /usr/share/nginx/html

# expose port 80
EXPOSE 80

# start nginx
CMD ["nginx", "-g", "daemon off;"]