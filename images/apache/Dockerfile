FROM php:7.2-apache
ADD --chown=www-data:www-data . /var/www/html
RUN sed -i 's/<Directory \/var\/www\/>/<Directory \/var\/www\/html>/g' /etc/apache2/apache2.conf 
