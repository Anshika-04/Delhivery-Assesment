FROM wordpress:latest
# Add PHP configurations
COPY wp-content/ /var/www/html/wp-content/
RUN echo "upload_max_filesize = 64M" > /usr/local/etc/php/conf.d/custom.ini
RUN echo "post_max_size = 64M" >> /usr/local/etc/php/conf.d/custom.ini

EXPOSE 80