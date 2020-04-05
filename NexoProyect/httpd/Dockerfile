FROM httpd:alpine
RUN apk update; \
    apk upgrade;
# Copy apache vhost file to proxy php requests to php-fpm container
#COPY index.html /var/www/html/

COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/

#COPY xero.cfg /usr/local/apache2/conf/xero.conf
#RUN echo "Include /usr/local/apache2/conf/xero.conf" \
#    >> /usr/local/apache2/conf/httpd.conf