FROM nginx:1.27.4-alpine

LABEL "Project"="BLOG-app"
LABEL "Author"="OWUSU-ADDAI"

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80/tcp

CMD ["nginx", "-g", "daemon off;"]
