FROM alpine:3.8
RUN apk update && apk add apache2 && mkdir /run/apache2 
ENV APACHE_PORT 80
COPY docker-entrypoint.sh /usr/bin/
ENTRYPOINT ["docker-entrypoint.sh"]
CMD ["httpd", "-D", "FOREGROUND"]
