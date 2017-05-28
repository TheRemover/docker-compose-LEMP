# docker-compose-LEMP

Docker-compose template for a LEMP stack. 

Uses the offical repositories for NGINX, PHP, and MySQL. 

## Update the following files: 

### site.conf

Add your server name to the server_name field

### docker-compose.yml

Change the MYSQL_ROOT password.<br>
Add a database with MYSQL_DATABASE.<br>
Add a user to the previous database wth MYSQL_USER. <br>
Set a password for the user with MYSQL_PASSWORD.<br>

## Change the file permissions for the code directory
sudo chown -R www-data:www-data code

## Start the LEMP stack:
sudo docker-compose up


