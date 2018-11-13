## Docker Guide

***

***

### Install Docker
* First uninstall all versions of **docker** or **docjer-engine** or **docker.io**

> `sudo apt -y remove docker docker-engine docker.io`


* Setup Docker Repository

> `sudo apt update`

> `sudo apt install -y apt-transport-https software-properties-common ca-certificates curl wget`

> `wget https://download.docker.com/linux/ubuntu/gpg `

> `sudo apt-key add gpg`

> `echo "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable" | sudo tee /etc/apt/sources.list.d/docker.list`

> `sudo apt update`


* Verify docker package is from the official repository.

> `sudo apt-cache policy docker-ce`


* Install Docker CE

> `sudo apt install -y docker-ce`


* Start docker service, if not start automatically

> `sudo systemctl start docker`
> `sudo systemctl enable docker`


* Verify docker version

> `docker --version`



***

### Allow Non-root user to run Docker
> `sudo groupadd docker`

* **NOTE:** Put your username in place of `<user_name>` **OR** write `$USER` to auto-detect current logged-in user.

> `sudo useradd <user_name>`
** OR **
> `sudo useradd $USER`

> `sudo usermod -aG docker <user_name>`
** OR **
> `sudo usermod -aG docker $USER`

* **IMPORTANT** Please Restart your device to take effect.

* Now you can run docker as non-root user. For example, Run following image:

> `docker run hello-world`


***
***

## For More, Goto: [Docker Get-Started Guide](https://docs.docker.com/get-started/) 


***
***

### Search and Kill running docker containers

> `ps aux | grep docker`

> `sudo kill pid_no`

