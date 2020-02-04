# database_app_dev_using_java

1. To change root password use the following command in phpmyadmin

      UPDATE mysql.user SET Password=PASSWORD('222') WHERE User='root';
      
2. If error or invalid setting in phpmyadmin page use the below procedure

Go inside your phpMyAdmin directory inside XAMPP installation folder. There will be a file called config.inc.php. Inside that file, find this line:

$cfg['Servers'][$i]['password'] = '';
