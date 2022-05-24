FROM centos:7
RUN yum install httpd
RUN yum install docker -y &&service docker start
EXPOSE 80
