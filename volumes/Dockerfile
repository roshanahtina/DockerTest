FROM centos:7
MAINTAINER roshan <roshan@linux.com>
RUN yum update -y
RUN mkdir /myvoldir
VOLUME /root/links-2.9/
CMD echo "This is a mount directory /myvoldir from container vol"

#docker run -it -v /root/DockerTraining/Xenial/:/myvoldir roshan/voldir:v1 /bin/bash
#links-2.9
#docker run -it -v /root/links-2.9:/myvoldir:ro roshan/voldir:v1 /bin/bash
