FROM nginx
RUN rm -f usr/share/nginx/html/index.html
RUN rm -f /etc/nginx/nginx.conf
RUN rm -f /etc/nginx/conf.d/default.conf
COPY default.conf /ect/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST = "catalogue"