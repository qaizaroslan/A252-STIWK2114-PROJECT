FROM php:8.2-apache
# Enable Apache routing features
RUN a2enmod rewrite
# Copy all your project files into the public server folder
COPY . /var/www/html/
# Give the server permission to read the files
RUN chown -R www-data:www-data /var/www/html
EXPOSE 80
