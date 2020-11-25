##It was an ordeal getting python 3.6 virtual environment working.

I had to reinstall git for windows to start with.

To create  a new virtualenv called "virtualenv" with python3.6 I typed in the git bash terminal:
virtualenv virtualenv -p /c/Users/David/Anaconda3/pkgs/python-3.6.12-h5500b2f_2/python.exe

This was after I created a virtualenv using conda. I think that installed python 3.6 first.
In the anaconda command prompt I typed
conda create --name tdd-python3p6 python=3.6
This created a conda virtual environment called tdd-python3p6.


Now that the virtualenv virtual environment called virtualenv is created here in 
C:\Users\David\Documents\Linear Consulting Limited\Clients\Stoic Strategies\Books\test_driven_dev_with_python\python-tdd-book>
type this to activate it: 
source virtualenv/Scripts/activate
This location didnt work for Django command line commands.

##NEW Work area
c/Users/David/Documents/Python/python-tdd-book

I deleted the previous virtual environment named virtualenv in Linear consulting workarea.
Create a new virtualenv 
"""
virtualenv virtualenv -p /c/Users/David/Anaconda3/pkgs/python-3.6.12-h5500b2f_2/python.exe


Install Django and Selenium
"""
pip install "django<1.12" "selenium<4"

$ eval "$(ssh-agent -s)"
$ ssh-add api key

git remote add origin https://github.com/pomeroyd/tdd-python-book.git
git branch -M main
git push -u origin main

