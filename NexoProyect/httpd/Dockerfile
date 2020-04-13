FROM httpd:alpine
RUN apk update; \
    apk upgrade;


COPY index.html /usr/local/apache2/htdocs/
COPY img/ /usr/local/apache2/htdocs/img/

COPY httpd.conf /usr/local/apache2/conf/