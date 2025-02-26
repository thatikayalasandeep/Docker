FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#ADD https://raw.githubusercontent.com/DAWS-82S/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
ADD https://pixabay.com/vectors/bee-cartoon-bumble-honey-icon-705412/ /usr/share/nginx/html/index.html
RUN chmod +xr /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]
