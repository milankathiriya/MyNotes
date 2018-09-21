## PostgeSQL Guide

***

***

### Install PostgreSQL
> `sudo apt-get install wget ca-certificates`

> `wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -`

> `sudo touch /etc/apt/sources.list.d/pgdg.list`

> `sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt/ $(lsb_release -cs)-pgdg main" > /etc/apt/sources.list.d/pgdg.list'`

> `sudo apt-get update && sudo apt upgrade`

> `sudo apt-get install postgresql-10 pgadmin4`


***

### Control PostgreSQL service
* To check status

> `sudo systemctl status postgresql`

* To start service

> `sudo systemctl start postgresql`

* To stop service

> `sudo systemctl stop postgresql`

* To restart service

> `sudo systemctl restart postgresql`


***

### Access PostgreSQL
> `sudo su -l postgres`

* Use `psql` for PostgreSQL interactive shell


***

### Secure PostgreSQL database
* Set password for linux user (postgres)

> `sudo passwd postgres`

* Set password for DBA (postgres)

> `su - postgres`
`psql`
`\password` **OR** `\password postgres`


***

***

##**For More, Goto:** [PostgreSQL Guide](https://www.itzgeek.com/how-tos/linux/ubuntu-how-tos/how-to-install-postgresql-10-on-ubuntu-18-04-lts.html)

***

***

### Start new pgadmin4 server
* First start pgadmin4

* Right click on Servers in Left sidebar and click Create > Server ...

* In General tab, enter any Name you want.

* In Connection tab, enter `localhost` in Host name/address. Enter Username (by default: postgres) and Password.

* Now hit save. Your server is now successfully created.




