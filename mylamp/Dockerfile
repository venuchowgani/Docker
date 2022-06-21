FROM centos:7
LABEL purpose="sri-cloud" author= "venu"
RUN yum install httpd -y && yum install php php-mysql -y && systemctl enable httpd.service
EXPOSE 80
CMD [ "sleep", "1d" ]