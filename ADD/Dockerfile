FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/thatikayalasandeep/Docker/blob/main/CMD/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]

# FROM almalinux:9

# RUN dnf install nginx -y && \
#     rm -rf /usr/share/nginx/html/index.html && \
#     curl -L -o /usr/share/nginx/html/index.html https://cdn.pixabay.com/download/image.jpg?filename=bee-cartoon-bumble-honey-icon-705412.png

# RUN chmod +xr /usr/share/nginx/html/index.html

# ADD sample-1.tar /tmp/
# CMD ["nginx", "-g", "daemon off;"]
