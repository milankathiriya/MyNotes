## MySQL Guide

***

***

### Install MySQL
* Adding the MySQL APT Repository

> `wget -c https://dev.mysql.com/get/mysql-apt-config_0.8.10-1_all.deb`

* Install MySQL repository package

> `sudo dpkg -i mysql-apt-config_0.8.10-1_all.deb`

* Now select your required options and hit Ok.

* Update package info

> `sudo apt-get update`

* Install MySQL

> `sudo apt-get install mysql-server`

* Between installation, You can choose your root password (can be also blank)

* Between installation, Choose your required authentication plugin 

* Now you all done.


***

### Secure MySQL Server
> `sudo mysql_secure_installation`

* Between installation, Choose your required options.


***
### Start and Enable MySQL
> `sudo systemctl start mysql`
> `sudo systemctl enable mysql`


***

### Control MySQL service
* To check status

> `sudo service mysql status`  
**OR**

> `sudo systemctl status mysql`

* To start service

> `sudo systemctl start mysql`  
**OR**

> `sudo service mysql start`  
**OR**

> `sudo start mysql`  
**OR**

> `sudo /etc/init.d/mysql start`


* To stop service

> `sudo systemctl stop mysql`  
**OR**

> `sudo service mysql stop`  
**OR**

> `sudo stop mysql`  
**OR**

> `sudo /etc/init.d/mysql stop`

* To restart service

> `sudo systemctl restart mysql`  
**OR**

> `sudo service mysql restart`  
**OR**

> `sudo restart mysql`  
**OR**

> `sudo /etc/init.d/mysql restart`


***

### Start with root user
> `sudo mysql -u root -p`


***

### Install additional MySQL Products and Components
> `sudo apt-get update`

> `sudo apt-get install <package-name>`

* Replace `<package_name>` with valid name of mysql packages you want to install. For Example:

> `sudo apt-get install mysql-workbench-community libmysqlclient20 mysql-connector-python-py3`



***

***

### For More, Goto: [Quick Guide for MySQL](https://www.tecmint.com/install-mysql-8-in-ubuntu/) 

***

### For More, Goto: [KickAss Guide to complete installation of MySQL](https://dev.mysql.com/doc/mysql-apt-repo-quick-guide/en/#apt-repo-fresh-install) 

***

***

