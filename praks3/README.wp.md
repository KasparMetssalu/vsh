<h1>Praktikum 3</h1>

<b>PHP5 ja PHP7 paigaldamine.</b>

//   Käivita järgmised käsud  //<br>
<code>	sudo apt-get install php5 libapache2-mod-php5 -y<br>
	sudo nano /etc/apt/sources.list<br>
	deb http://packages.dotdeb.org jessie all<br>
	deb-src http://packages.dotdeb.org jessie all<br>
	sudo apt-get install php7.0 php7.0-common libapache2-mod-php7.0 -y<br>
</code>
<br><b>MYSQL 5.6 Paigaldamine.</b>

// Paigaldamiseks käivita järgmised käsud //<br>
	<code>wget https://dev.mysql.com/get/mysql-apt-config_0.8.9-1_all.deb</code><br>
	<code>dpkg -i mysql-apt-config_0.8.9-1_all.deb</code>
	<code>sudo apt-get update</code><br>
	<code>sudo apt-get install mysql-community-server -y</code><br>
MYSQLi root kasutaja parooliks valisin: qwerty<br>
	<code>a2dismod php5</code><br>
	<code>service apache2 restart</code><br>
	<code>a2enmod php7.0</code><br>
	<code>service apache2 restart</code><br>

<b>PHPMyAdmin paigaldamine.</b><br>
	<code>sudo apt-get install mcrypt -y</code><br>
	<code>sudo service apache2 restart</code><br>
	<code>sudo apt-get install phpmyadmin</code><br>

<b>PHP lehe koostamise kood</b><br>
	<code>
	<?php
	phpinfo();
	$tervitus = "Hello world!";
	echo $tervitus;
	?>
