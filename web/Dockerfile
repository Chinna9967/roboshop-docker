FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
# reverse proxy configuration
COPY roboshop.conf /etc/nginx/deafult.d/roboshop.conf 
ADD static /usr/share/nginx/html/