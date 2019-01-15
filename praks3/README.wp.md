<h1>Praktikum 3</h1>

<b>PHP5 ja PHP7 paigaldamine.</b>

//   Käivita järgmised käsud  //
<code>	<p>sudo apt-get install php5 libapache2-mod-php5 -y</p>
	<p>sudo nano /etc/apt/sources.list</p>
	<p>deb http://packages.dotdeb.org jessie all</p>
	<p>deb-src http://packages.dotdeb.org jessie all</p>
	<p>sudo apt-get install php7.0 php7.0-common libapache2-mod-php7.0 -y</p>
</code>
<b>MYSQL 5.6 Paigaldamine.</b>

// Paigaldamiseks käivita järgmised käsud //
	<code>wget https://dev.mysql.com/get/mysql-apt-config_0.8.9-1_all.deb</code><br>
	<code>dpkg -i mysql-apt-config_0.8.9-1_all.deb</code>
