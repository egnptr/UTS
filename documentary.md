Documentary for UTS 
All the Commands and steps used (the commands are step by step):

Package Install
    sudo apt install nginx
    sudo apt-get update
    sudo apt install git
    sudo apt instal nginx
    sudo apt install nginx mariadb-server mariadb-client php7.2 php7.2-fpm
    sudo enable systemctl enable nginx
    sudo service nginx start
    sudo service mysql start
    sudo service service php7.2-fpm start
    sudo mysql_seucure_installation
    All questions answered with Yes

Nginx Server Setup  
   cd /etc/nginx/sites-available/
    sudo cp default midtest
    sudo chmod +w default
    sudo nano default{
        Listen 80 is kept and the rest are removed
        Added index.php
        uncomment the location ~\.php$ block
    }
    sudo nginx -t
    sudo ln -s /etc/nginx/sites-available/midtest /etc/nginx/sites-enabled/
    sudo unlink /etc/nginx/sites-enabled/default
    sudo service nginx reload
    cd /var/www/html/
    cd sudo nano info.php{
        <?php phpinfo(); ?>
    }
    curl -4 icanhazip.com
    Ip: 122.200.1.254
    cd ~
    sudo rm info.php
    info.php has been removed


    





    


    



