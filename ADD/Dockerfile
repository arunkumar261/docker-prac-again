FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY index.html /usr/share/nginx/html/
ADD https://raw.githubusercontent.com/daws-76s/dockerfiles/main/COPY/Dockerfile /tmp/
CMD ["nginx", "-g", "daemon off;"]