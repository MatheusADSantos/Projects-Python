# Projects-Python
## Some Automation with Python
## Get Starte: 

###**How to set Python3 as a default python version on MacOS?**
https://dev.to/malwarebo/how-to-set-python3-as-a-default-python-version-on-mac-4jjf#:~:text=Open%20the%20terminal%20(bash%20or,https%3A%2F%2Fbrew.sh).&text=Look%20where%20it%20is%20installed.&text=Change%20the%20default%20python%20symlink,want%20to%20use%20from%20above.

## **https://mnzel.medium.com/how-to-activate-python-venv-on-a-mac-a8fa1c3cb511**
https://mnzel.medium.com/how-to-activate-python-venv-on-a-mac-a8fa1c3cb511

### **- Instal Venv**
https://www.youtube.com/watch?v=m1TYpvIYm74

mkdir proeject
cd project

# To check version
python --version or python -V

# If your default python's version 3
pip install virtualenv
# Else you can run
pip3 install virtualenv

# In linux to install python3 venv
sudo apt install python3-venv # Linux
sudo apt install python3-venv # Mac

# To create my virtual enviroment
python -m venv /path/to/new/virtual/nameVirtualEnviroment

# To activate my virtual enviroment
source env/bin/activate

# Now we can install/uninstall packages inside venv, like:
pip install pymysql
pip uninstall pymysql

# Then your packages installed, been stay in env/lib/
# Now you can run script python, like:
python script.py

# To deactive venv
deactivate



## 1st Project
In this first project we'll do automation from instagram
- In specific post, we'll mark all friends in my social midia 
    - One by one ... 
