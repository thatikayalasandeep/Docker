FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.linkedin.com/in/thati
kayala-sandeep /usr/share/nginx/html/index.html
RUN chmod +R /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
