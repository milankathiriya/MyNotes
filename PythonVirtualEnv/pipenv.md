# pipenv guide

---
---

### Install pipenv
* For Windows OS:
>`pip install pipenv`

* For Mac / Linux OS (with Python3):
>`pip3 install pipenv`

>**OR**

>`sudo pip3 install pipenv`

---

### Create Virtual Environment
* Change directory into which you want to create Virtual Environment

* For Example:

>`cd Desktop\myenv`

* Now Create Virtual Environment for current directory, this will create virtual env named "myvenv"
>`pipenv install`

* Create Virtual Environment with specific python version
>`pipenv --python <version>`

---

### Activate Virtual Environment
>`pipenv shell`

---

### Deactive Virtual Environment
>`exit`

---

### Remove Virtual Environment
>`pipenv --rm`

---

### Install any packages / libraries
>`pipenv install <package_name>`
* e.g. `pipenv install numpy`

---

### Remove any packages / libraries
>`pipenv uninstall <package_name>`
* e.g. `pipenv uninstall numpy`

* Remove all packages
>`pipenv uninstall -all`

---

### To see a dependancy graph
>`pipenv graph`

---

### Generate Lockfile (assure all dependancies from Pipfile are installed and updated)
>`pipenv lock`

---

### Install all packages from existing Pipfile
>`pipenv install`

* To install all dev dependancies
>`pipenv install --dev`

---

### Output Project Home Information
>`pipenv --where`

---

### Output Virtual Environment Information
>`pipenv --venv`

---

### Using pip commands in pipenv
>`pipenv run pip <pip_command>`

* e.g. `pipenv run pip list`

---

### Generate requirements.txt file from Pipfile
* Add all installed packages into requirements.txt
>`pipenv lock -r > requirements.txt`

* Add all dev dependancies into requirements.txt
>`pipenv lock -r -d > dev-requirements.txt`

---

### Install packages from requirements.txt
* Install all packages from requirements.txt
>`pipenv install -r requirements.txt`

* Add all dev dependancies into requirements.txt
>`pipenv install -r dev-requirements.txt --dev`

---