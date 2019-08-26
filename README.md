# joomla
joomla php.ini for production env. 

Usage : 
<pre>nginx:alpine
joomla/nginx/server2.conf:/etc/nginx/conf.d/default.conf:ro
joomla/php/myjoomla.ini:/usr/local/etc/php/conf.d/myjoomla.ini:ro
joomla/html/:/var/www/html/

dockuru101/joomla:php7.3-fpm-alpine
joomla/php/myjoomla.ini:/usr/local/etc/php/conf.d/myjoomla.ini:ro
joomla/html/:/var/www/html/</pre>
