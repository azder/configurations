
From [Install Curl Extension for PHP in Ubuntu](http://buzznol.blogspot.com/2008/12/install-curl-extension-for-php-in.html)

    sudo apt-get install curl libcurl3 libcurl3-dev php5-curl

After installing libcurl you should restart the web server with one of the following commands,

    sudo /etc/init.d/apache2 restart
OR

    sudo service apache2 restart
