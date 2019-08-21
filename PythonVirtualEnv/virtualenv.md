# virtualenv guide

---
---

### Install virtualenv
* For Windows OS:
>`pip install virtualenv`

* For Mac / Linux OS (with Python3):
>`pip3 install virtualenv`

>**OR**

>`sudo pip3 install virtualenv`

---

### Create Virtual Environment
* Change directory into which you want to create Virtual Environment

* For Example:

>`cd Desktop`

* Now Create Virtual Environment named "venv"

>`virtualenv venv`

* Create virtual environment with specific Python version:

>`virtualenv -p python3 venv`

>**OR**

>`virtualenv -p python2 venv`

---

### Activate Virtual Environment
* For Windows:

>`venv\Scripts\activate`

* For Mac / Linux:

>`source venv/bin/activate`

---

### Deactivate Virtual Environment
* For Windows / Mac / Linux:

>`deactivate`

---

### Remove Virtual Environment
* For Mac / Linux:

>`rm -rf venv`

>**OR**

>`sudo rm -rf venv`

* For Windows:

>`rmdir venv /s`