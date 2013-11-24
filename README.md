README
======

This is a very simple PHP (2 script) webserver, created using the original code from Benjamin Maynor.

To run this server, clone the repository (or fork if you want to modify), by running

> git clone git://github.com/aroemen/php-web-server.git

Then start the server by running

add an alias in your ~/.bash_profile like:
> alias php-web-server="php ~/php-web-server/server.php"

then `cd` the dir of source code and run:
> $ php-web-server

for example:

![demo](http://i.imgur.com/KczA0qL.png)


There are _some_ custom rewrite rules for symfony which may require modification, but the server should run.

** You must have the php-cgi binary in your path for this to work **

