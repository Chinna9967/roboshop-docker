FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/ngnx/conf.d/deafult.conf
# reverse proxy configuration
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/