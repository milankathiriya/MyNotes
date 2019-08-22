# virtualenvwrapper guide

---
---

### Install virtualenvwrapper
* For Windows OS:
>`pip install virtualenv`

* For Linux OS (with Python3):
>`pip3 install virtualenvwrapper`

>**OR**

>`sudo pip3 install virtualenvwrapper`

* For Mac OS (with Python3):
>`sudo pip3 install virtualenvwrapper`

* **RESTART CMD / TERMINAL**

---

## Only for Mac / Linux:
### Add virtualenvwrapper to .bashrc file for accessing it
* Once virtualenvwrapper is installed, look for the the directory of virtualenvwrapper.sh by entering 
>`which virtualenvwrapper.sh`

* Once this is done, this should output something like this in Linux:
**/usr/local/bin/virtualenvwrapper.sh**

**OR**

* In Mac: 
**/Library/Frameworks/Python.framework/Versions/3.7/bin/virtualenvwrapper.sh**

* Open .bash_profile file
>`nano ~/.bash_profile`

* **For Mac:** Add below lines to ~/.bash_profile file:
>`export WORKON_HOME=$HOME/.virtualenvs`

>`export VIRTUALENVWRAPPER_PYTHON=/Library/Frameworks/Python.framework/Versions/3.7/bin/python3`

>`source /Library/Frameworks/Python.framework/Versions/3.7/bin/virtualenvwrapper.sh`

* **For Linux:** Add below lines to ~/.bash_profile file:
>`export WORKON_HOME=$HOME/.virtualenvs`

>`export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3`

>`source ~/.local/bin/virtualenvwrapper.sh`

* The .virtualenvs directory can be named as you want.
* To set VIRTUALENVWRAPPER_PYTHON's value, look for the the directory of python3 by entering
>`which python3`

* **On Mac**, Once this is done, this should output something like this: **/Library/Frameworks/Python.framework/Versions/3.7/bin/python3**

* **On Linux**, Once this is done, this should output something like this: **/usr/bin/python3**

* After that re-apply all changes in .bash_profile
>`source ~/.bash_profile`

* **RESTART CMD / TERMINAL**

---

## To create Virtul Environment with default Python version
>`mkvirtualenv myvenv`

---

## To create Virtul Environment with specific Python version
>`mkvirtualenv --python=<your_python_path> myvenv`
* e.g `mkvirtualenv --python=/usr/local/bin/python3 myvenv`

>**OR**

>`mkvirtualenv -p <your_python_version> myvenv`
* e.g `mkvirtualenv -p python3 myvenv`

---

## Activate Virtul Environment
>`workon myvenv`

---

## Deactivate Virtul Environment
>`deactivate myvenv`

---

## List all available Virtul Environments
>`lsvirtualenv`

---

## Remove Virtul Environment
>`rmvirtualenv myvenv`






