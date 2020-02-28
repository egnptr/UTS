#Documentary for UTS 
**All the Commands and steps used (the commands are step by step):

##Package Install
    - sudo apt install nginx
    - sudo apt-get update
    - sudo apt install git
    - sudo apt instal nginx
    - sudo apt install nginx mariadb-server mariadb-client php7.2 php7.2-fpm
    - sudo enable systemctl enable nginx
    - sudo service nginx start
    - sudo service mysql start
    - sudo service service php7.2-fpm start
    - sudo mysql_seucure_installation
    - All questions answered with Yes

##Nginx Server Setup  
    - cd /etc/nginx/sites-available/
    - sudo cp default midtest
    - sudo chmod +w default
    - sudo nano default:
        - Listen 80 is kept and the rest are removed
        - Added index.php
        - uncomment the location ~\.php$ block
    - sudo nginx -t
    - sudo ln -s /etc/nginx/sites-available/midtest /etc/nginx/sites-enabled/
    - sudo unlink /etc/nginx/sites-enabled/default
    - sudo service nginx reload
    - cd /var/www/html/
    - cd sudo nano info.php:
        - <?php phpinfo(); ?>
    - curl -4 icanhazip.com
    - Ip: 122.200.1.254
    - cd ~
    - sudo rm info.php
    - info.php has been removed

##Lion Wiki
    - wget http/lionwiki.0o.cz/download/3.2.11/lionwiki-3.2.11.zip
    - sudo apt install unzip
    - unzip lionwiki-3.2.11.zip
    - cd lionwiki-3.2.11
    - ls -l
    - sudo chmod a+w var
    - ls -l
    - cd ..
    - sudo mv lionwiki-3.2.11 /var/www/html
    - cd /var/www/html
    - ls
    - cd lionwiki-3.2.11
    - ls
    - cd templates
    - ls -l

    Inserted in browser: localhost/lionwiki-3.2.11
    The Lion wiki main page is successfully shown
    Added an introduction at the main page
    { Hello, This is the main page
      There are two pages: Luis's Information [Luis] and Eugene's Information [Eugene].
      Feel free to check each of them.}

    Links that will move users to a new page consisting
    of our information have been created. [Click the link to
    move to our pages]
    





    


    



