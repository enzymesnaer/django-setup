# django-setup
A simple batch file

Simple batch script for creating project,  making migrations & running server
Modify and paste below code in a file with .bat extension and then run

@echo off
cmd /k "cd /d C:\Users\snehar\Desktop\myenv\Scripts & activate & cd /d C:\Users\snehar\Desktop\myenv & pip install django & django-admin startproject projectdir . & django-admin startapp appdir & python manage.py makemigrations & python manage.py migrate & python manage.py runserver"


or


@echo off
cmd /k "cd /d C:\Users\Snehar\Desktop\ & python -m venv myenv & cd /d C:\Users\Snehar\Desktop\myenv\Scripts & activate & cd /d C:\Users\Snehar\Desktop\myenv & pip install django & django-admin startproject  testroot . & django-admin startapp testapp & python manage.py makemigrations & python manage.py migrate & python manage.py runserver"

