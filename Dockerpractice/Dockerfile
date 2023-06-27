FROM httpd:latest
RUN echo "LoadModule headers_module modules/mod_headers.so" >> /usr/local/apache2/conf/httpd.conf
COPY .htaccess /var/www/html/.htaccess
COPY index.html /var/www/html/index.html
COPY css/ /var/www/html/css