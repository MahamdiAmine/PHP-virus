# PHP-virus

Self replicating virus.


If you have php 7.3 installed in your system , run :

```
$ sudo apt-get install mcrypt php7.3-mcrypt
$ sudo pecl install mcrypt-1.0.2
$ sudo bash -c "echo extension=/usr/lib/php/20180731/mcrypt.so > /etc/php/7.3/cli/conf.d/mcrypt.ini"

```


## to test : 
```
$php virus.php

```
