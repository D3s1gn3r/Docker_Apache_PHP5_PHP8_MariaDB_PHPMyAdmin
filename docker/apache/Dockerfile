FROM httpd:2.4.51

COPY two-php.apache.conf /usr/local/apache2/conf/two-php.apache.conf

RUN echo "Include /usr/local/apache2/conf/two-php.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf