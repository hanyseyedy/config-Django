# Config Django in Ubuntu:

## first need to install pip
`sudo apt install python3-pip`

## install virtualenv:
install: `sudo apt install virtualenv`<br>
set python interpreter: `virtualenv -p python3 venv`<br >
activate vtrtualenv: `source venv/bin/activate`

## install Django: 
`pip install django=="version"`<br >
example: `pip install django==4.0.4`<br >
or Last version: `pip install django`

## Django commands list:
`django-admin`

## start project:
`django-admin startproject "your project name"`<br >
example: `django-admin startproject MyProject`

## start and run project:
`cd MyProject`<br >
run server: `./manage.py runserver` or `python3 manage.py runserver` <br >

## run some migrations like sqlite3:
`./manage.py migrate`<br >

to stop server: `CONTROL-C`

## create admin user:
`./manage.py createsuperuser`<br >
then insert username, email and password
