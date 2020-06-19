FROM centos

RUN yum install httpd -y

COPY webpage/ /var/www/html

CMD /usr/sbin/httpd -DFOREGROUND
