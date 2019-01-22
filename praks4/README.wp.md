<h1>HTTPS instaleerimine</h1>

mkdir /etc/apache2/ssl<br>
openssl req -x509 -nodes -days 1095 -newkey rsa:2048 -out /etc/apache2/ssl/apache.crt -keyout /etc/apache2/ssl/apache.key<br>
a2enmod ssl<br>
ln -s /etc/apache2/sites-available/default-ssl.conf /etc/apache2/sites-enabled/000-default-ssl.conf<br>
nano /etc/apache2/sites-enabled/000-default-ssl.conf<br>
