# LampStack-
Lampstack installion made easy

#! /bin/bash
sudo apt-get update
sudo apt-get install apache2
sudo apt-get install mysql-server php5-mysql
sudo mysql_install_db --explicit_defaults_for_timestamp
sudo mysql_secure_installation
sudo apt-get install php5 libapache2-mod-php5 php5-mcrypt
sudo nano /etc/apache2/mods-enabled/dir.conf
sudo service apache2 restart
sudo apt-get install php5-cli
sudo apt-get update
sudo apt-get install phpmyadmin
sudo apt-get install php5-curl
sudo php5enmod mcrypt
sudo service apache2 restart
sudo echo 'Include /etc/phpmyadmin/apache.conf' >> /etc/apache2/apache2.conf
sudo service apache2 restart
sudo a2enmod rewrite
sudo service apache2 restart
sudo apt-get install git

##run this as shell script


