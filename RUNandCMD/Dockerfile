FROM docker.io/centos:7
MAINTAINER roshan@linuxacedamy.com
RUN yum install httpd -y
RUN yum install -y net-tools wget
RUN echo "This is first HTTPD web server in Docker container" > /var/www/html/index.html && systemctl start httpd
CMD echo "Good that we are achived"
