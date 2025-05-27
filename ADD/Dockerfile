FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/VENKATESH47422/dockerfiles/refs/heads/main/CMD/Dockerfile /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]