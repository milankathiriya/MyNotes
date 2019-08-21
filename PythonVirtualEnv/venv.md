# venv guide

---
---

### Create Virtual Environment
* Change directory into which you want to create Virtual Environment

* For Example:

>`cd Desktop`

* Now Create Virtual Environment named "myvenv"

* For Windows OS:

>`python -m venv myvenv`

* For Mac / Linux OS (with python3):

>`python3 -m venv myvenv`
---

### Create Virtual Environment with System global packages
* Change directory into which you want to create Virtual Environment

* For Mac / Linux OS (with python3):

>`python3 -m venv myvenv --system-site-packages`

* List only venv level packages instead of both local+global:

>`pip list --local`

---

### Activate Virtual Environment
* For Windows:

>`myvenv\Scripts\activate.bat`

* For Mac / Linux:

>`source myvenv/bin/activate`

---

### Deactivate Virtual Environment
* For Windows / Mac / Linux:

>`deactivate`

---

### Remove Virtual Environment
* For Mac / Linux:

>`rm -rf myvenv`

>**OR**

>`sudo rm -rf myvenv`

* For Windows:

>`rmdir myvenv /s`