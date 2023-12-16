# for installing djangorest_framework thsee are required
1.python
2.pip 
3.django

#COMMANDS 1 sudo apt update & sudo apt upgrade

2  sudo apt install python3

3  sudo apt install python3-venv

4  python3 -m venv env

5  . env/bin/activate

6  pip install djangorestframework

7  django-admin startproject geeksforgeeks
To initialize REST Framework in your project, go to settings.py, and in INSTALLED_APPS add ‘rest_framework’ at the bottom to create api in python django.

Application definition
INSTALLED_APPS = [ 'django.contrib.admin', 
'django.contrib.auth', 
'django.contrib.contenttypes',
'django.contrib.sessions', 
'django.contrib.messages', 
'django.contrib.staticfiles',
'rest_framework', ]

#Create a app

python manage.py startapp apis

add apis
INSTALLED_APPS = [ 'django.contrib.admin', 
'django.contrib.auth',
'django.contrib.contenttypes', 
'django.contrib.sessions',
'django.contrib.messages',
'django.contrib.staticfiles', 
'rest_framework', 'apis', ]

#for structure of project

sudo apt install tree
├── apis

│   ├── __init__.py

│   ├── admin.py

│   ├── apps.py

│   ├── migrations

│   │   └── __init__.py

│   ├── models.py

│   ├── tests.py

│   └── views.py
├── geeksforgeeks

│   ├── __init__.py

│   ├── __pycache__

│   │   ├── __init__.cpython-310.pyc
│   │   └── settings.cpython-310.pyc

│   ├── asgi.py

│   ├── settings.py

│   ├── urls.py

│   └── wsgi.py

└── manage.py


#commands

python manage.py makemigrations

python manage.py migrate

In setting ALLOWED HOST ADD PUBLIC IP
python manage.py runserver private ip:8000

#visit browser by public

#OUTPUT

![Screenshot (35)](https://github.com/vaishnavikapile22/API-using-djangorest_framework/assets/149785862/1bd3ab15-d177-4dac-9498-fb15909d0a0e)
