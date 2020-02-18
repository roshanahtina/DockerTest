FROM centos:latest
MAINTAINER roshan < roshan@linuxacedamy.com >
RUN yum update -y && yum clean all
RUN yum install systemd httpd net-tools wget httpd-tools -y
RUN echo "This is first HTTPD web server in Docker container" > /var/www/html/index.html
EXPOSE 80
CMD ["/usr/sbin/init"]
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
CMD echo "Good that we are achived expose httpd web server...!"
