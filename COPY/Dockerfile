FROM almalinux:8
RUN yum install epel-release -y
RUN yum install nginx -y
RUN rm -f /usr/share/nginx/html/index.html
COPY website-1 /usr/share/nginx/html
CMD ["nginx","-g","daemon off;"]