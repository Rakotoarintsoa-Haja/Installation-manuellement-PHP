# Installation-manuellement-PHP
Installation manuellement PHP
Ceci est un procedure d'installation de PHP 
Installer d'abord ceci : 
libsml2 et sqlite3 sont des dépendances de PHP 


Télécharger le fichier code source dans le ce site : https://xmlsoft.org/libsml2
$tar -xfv libsml2.tar.gz
$cd libsml2
$ ./configure 
$ make 
$ make install 


https://www.sqlite3.org/downloads.html
$ ./confige --prefix=/usr/local/sqlite3
$ make
$ sudo make install

Maintenant le télécharger le code source dans le site : https://www.php.net/downloads.php 
Maintenant décompresser le et desarchiver : $tar -xfv php-8.3.6.tar.gz 
$cd php-8.3.6
1)$ ./configure
2)$ make
3)$ make install


