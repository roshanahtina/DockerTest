FROM centos:latest
MAINTAINER roshan <roshan@linux.com>
RUN yum update -y
RUN yum install -y httpd net-tools
CMD echo "This is a custom build page for an images from LA Apache server" > /var/www/html/index.html
EXPOSE 80
ENTRYPOINT apachectl "-DFOREGROUND"
