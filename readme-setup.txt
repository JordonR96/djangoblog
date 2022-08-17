create venv in desired directory using
$ python3 -m venv env_name

start it by running

$ source myvenv/bin/activate

upgrade pip using

(env_name) ~$ python -m pip install --upgrade pip

create requirements.txt in directory and add following
Django~=3.2.10


run pip install -r requirements.txt to install Django
ß

once thats done 

run in terminal

django-admin startproject mysite

mysite is just the name of project