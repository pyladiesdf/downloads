# DjangoGirls Tutorial

Blog app from Django girls tutorial.

## Configuration

### Start VE

'''
$ python3 -m venv venv
$ source venv/bin/activate
'''

### Install basic environment

'''
$ pip install --upgrade pip
$ pip install django~=1.9.0
'''

### Start Django project

The first command start the project and the second create a module to act like a blog.

'''
$ django-admin startproject proj .
$ python manage.py startapp blog
$ python manage.py createsuperuser
'''

## Database

### Create

'''
$ python manage.py makemigrations blog
'''

### Update database

'''
$ python manage.py migrate
'''

## Run

After run the command bellow the server will be up on the address http://127.0.0.1:8000/.

'''
$ python manage.py runserver
'''
