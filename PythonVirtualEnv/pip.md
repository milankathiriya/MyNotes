# pip (Pip Package Manager)

---
---

### Install pip
* **NOTE:** pip is pre-installed with Python 3.
* For Mac / Linux:
>`pip install pip`

>**OR**

>`sudo pip install pip3`

---

### Check Pip version:
>`pip --version`

>**OR**

>`pip3 --version`

---

### Install any package / library:
* For Windows OS:
>`pip install <package_name>`
* e.g. `pip install numpy`

* For Mac / Linux:

>`pip3 install <package_name>`
* e.g. `pip3 install numpy`

>**OR**

>`sudo pip3 install <package_name>`
* e.g. `sudo pip3 install numpy`

---

### List / Show all installed packages
* For Windows OS:
>`pip list`

>**OR**

>`pip freeze`

* For Mac / Linux:
>`pip3 list`

>**OR**

>`pip3 freeze`

---

### Generate requirements.txt file for listing all installed packages
* For Windows OS:
>`pip freeze > requirements.txt`

* For Mac / Linux:
>`pip3 freeze > requirements.txt`

---

### Install packages from requirements.txt
* For Windows OS:
>`pip install -r requirements.txt`

>**OR** **Install with Updates**

>`pip install -U -r requirements.txt`

* For Mac / Linux:
>`pip3 install -r requirements.txt`

>**OR** **Install with Updates**

>`pip3 install -U -r requirements.txt`