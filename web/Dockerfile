FROM centos:latest

# Install PHP5.6 & Apache
RUN yum install php php-devel php-gd php-xml php-mbstring php-opcache php-mcrypt php-mysqlnd -y

# Clear yum cache
RUN yum clean all

# for web
EXPOSE 80

CMD /usr/sbin/httpd -DFOREGROUND
