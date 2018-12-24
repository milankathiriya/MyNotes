## Python Guide

***

***

### Install Python3
> `sudo apt install python3`


***

### Update Python3 (includes pip3)
* Download [Python3 Source Code](https://www.python.org/downloads/source/)

> `cd Downloads `

> `tar -xf Python-3.7.1.tar.xz`

> `cd Python-3.7.1`

> `./configure`

> `make`

> `sudo make install`


***

### Install some useful dependencies

> `sudo apt install build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev xz-utils tk-dev python3-distutils`

* Now in the downloaded python source rebuild and install python with the following command: 

> `./configure --enable-loadable-sqlite-extensions && make && sudo make install`
***


### Install IDLE3
> `sudo apt install idle-python3.7`


***

### pip3

* Check pip version:

> `pip3 --version`

* Now install any package with pip like:

> `pip3 install <package_name> --user`


***

### Install pipenv (includes virtualenv)
> `pip3 install pipenv --user`


***

### Install bpython3 interpreter
> `sudo apt install bpython3`


***

### Install jupyter notebook
> `pip3 install jupyter --user`


***

* Restart your terminal or device
