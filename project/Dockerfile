FROM busybox
MAINTAINER shaghuf <shaghuf@gmail.com>
EXPOSE 8800
ADD index.html /www/index.html
CMD httpd -p 8800 -h /www; tail -f /dev/null
