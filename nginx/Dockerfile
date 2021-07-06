FROM nginx:1.21.1

RUN mkdir /wwwroot
COPY ./nginx.conf /etc/nginx/nginx.conf

RUN service nginx start
