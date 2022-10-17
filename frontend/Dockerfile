FROM centos:7
#update and install nginx section
RUN yum update -y
RUN yum install -y epel-release
RUN yum install -y nginx


COPY index.html /usr/share/nginx/html

EXPOSE 80/tcp

CMD ["nginx", "-g", "daemon off;"]