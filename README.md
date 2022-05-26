# Projects-Python
##Some Automation with Python

##Get Starte: 

###**How to set Python3 as a default python version on MacOS?**
https://dev.to/malwarebo/how-to-set-python3-as-a-default-python-version-on-mac-4jjf#:~:text=Open%20the%20terminal%20(bash%20or,https%3A%2F%2Fbrew.sh).&text=Look%20where%20it%20is%20installed.&text=Change%20the%20default%20python%20symlink,want%20to%20use%20from%20above.

##**https://mnzel.medium.com/how-to-activate-python-venv-on-a-mac-a8fa1c3cb511**
https://mnzel.medium.com/how-to-activate-python-venv-on-a-mac-a8fa1c3cb511

###**- Instal Venv**
https://www.youtube.com/watch?v=m1TYpvIYm74

- To check version
python --version | python -V

- If your python from default is 3... then
pip install virtualenv
Else you can run
pip3 install virtualenv

- To create a virtual env
python -m venv /path/to/new/virtual/nameVirtualEnviroment

- To active virtualenv, in this case -> 'venv'
source venv/bin/activate

- After activeted... Lets install some packeges!
pip install <package>
like: pip install time

- Now we can run script
python scrap_instagran_duxamego.py 



###1st Project
In this first project we'll do automation from instagram
- In specific post, we'll mark all friends in my social midia 
    - One by one ... 
