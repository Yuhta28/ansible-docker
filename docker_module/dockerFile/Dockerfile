FROM centos
LABEL test
RUN yum -y install httpd
RUN yum clean all
COPY index.html /var/www/html/index.html
RUN sudo systemctl start httpd
RUN sudo systemctl enable httpd
