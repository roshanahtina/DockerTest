FROM docker.io/centos:7
MAINTAINER roshan@linuxacedamy.com
RUN yum update all
RUN yum install httpd -y
RUN yum install -y net-tools wget
RUN echo "This is first HTTPD web server in Docker container" > /var/www/html/index.html 
RUN systemctl start httpd
EXPOSE 8080:80
#CMD ['httpd', 'start']
CMD echo "Good that we are achived"
