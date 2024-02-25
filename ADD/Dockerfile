FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/sridevi2009/notes/master/demo-session.txt /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]
