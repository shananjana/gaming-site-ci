# Stage 1: just copy static site
FROM nginx:1.21-alpine
COPY . /usr/share/nginx/html
# COPY nginx.conf /etc/nginx/conf.d/default.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
