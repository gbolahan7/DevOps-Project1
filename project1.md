## Project 1 Documentation

# STEP 1 - INSTALLING APACHE AND UPDATING THE FIREWALL
`sudo apt update`
`sudo apt install apache2`


## verification of apache2 running as a service
`sudo systemctl status apache2`
![Apache status](./images/apache_status.PNG)

## Accessing server locally
`curl http:localhost:80`
![curl access](./images/curl-access.PNG)

## Accessing server on the web
`http://<Public-IP-Address>:80`
![apache ui](./images/apache-ui.PNG)





# STEP 2 - INSTALLING MYSQL
`$ sudo apt install mysql-server`
`$ sudo mysql`

## Interactive Script
`$ sudo mysql_secure_installation`

## Login test into MYSQL Console
`$ sudo mysql -p`
![mysql](./images/mysql-install...PNG)




# STEP 3 - INSTALLING PHP

## Installing the necessary php and some dependency packages
`sudo apt install php libapache2-mod-php php-mysql`

## Confirming the PHP Version
`php -v`
![php](./images/php-install.PNG)
