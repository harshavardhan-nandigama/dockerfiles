FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/harshavardhan-nandigama/harshavardhan-nandigama.git
CMD ["nginx", "-g", "daemon off;"]