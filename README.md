# path

FROM httpd
        COPY * /usr/local/apache2/htdocs/


FROM nginx
        COPY * /usr/share/nginx/html/


FROM ubuntu/apache2
        COPY * /var/www/html/
