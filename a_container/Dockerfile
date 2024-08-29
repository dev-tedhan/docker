FROM nginx:1.27.1-alpine
COPY index-with-logo.html /usr/share/nginx/html/index.html
COPY docker.png /usr/share/nginx/html/docker.png
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
