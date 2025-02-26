FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
ADD https://pixabay.com/illustrations/motorcycle-yellow-sketch-vehicle-6669454/ usr/share/nginx/html/index.html
# ADD https://www.linkedin.com/in/thatikayala-sandeep usr/share/nginx/html/index.html
RUN chmod +r usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
