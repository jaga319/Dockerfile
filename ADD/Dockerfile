FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/jaga319/roboshop-ansible/main/cart.service /tmp
ADD sample.tar /tmp
CMD ["nginx", "-g", "daemon off;"]