FROM docker.io/centos:7
MAINTAINER roshan < roshan@linuxacedamy.com >
RUN yum update -y
RUN yum install httpd net-tools wget -y
RUN echo "This is first HTTPD web server in Docker container" > /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
CMD echo "Good that we are achived expose httpd web server...!"
