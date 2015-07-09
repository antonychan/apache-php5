```
FROM antonychan/apache-php5

ADD . /var/www/html/

EXPOSE 80

CMD ["apache2", "-DFOREGROUND"]

```
