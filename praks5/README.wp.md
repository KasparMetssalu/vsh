<h1>VSH Praks 5</h1>

cd /var/www/html<br>
wget https://wordpress.org/latest.zip<br>
unzip -q latest.zip<br>
chown -R www-data:www-data /var/www/html/wordpress<br>
chmod -R 775 /var/www/html/wordpress<br>
chown -R www-data:www-data /var/www/html/wordpress/wp-content/uploads<br>

<h1>MYSQL</h1>
mysql -u root -p<br>
CREATE DATABASE wordpress_sample;<br>
CREATE USER wp_user@localhost IDENTIFIED BY 'qwerty';<br>
GRANT ALL PRIVILEGES ON wordpress_samle.* TO wp_user@localhost;<br>
FLUSH PRIVILEGES;<br>
exit<br>
