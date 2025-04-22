# Project

Create a polling app with Django to understand project structures

Create a Pool Question
Create a Choice from Question
Create a Endpoint to Question details
Create a Form for vote
Crete a Tests

## Getting started Django 5.2

# Objective 

Assimate new dajango Updates

https://docs.djangoproject.com/en/5.2/intro/


### Support Material

    https://alicecampkin.medium.com/how-to-set-up-environment-variables-in-django-f3c4db78c55f

    https://builtwithdjango.com/blog/env-vars

    https://www.google.com/search?q=django+undo+migration&oq=django+unmigrate&gs_lcrp=EgZjaHJvbWUqCggCEAAYgAQYogQyBggAEEUYOTIMCAEQABgKGBMYFhgeMgoIAhAAGIAEGKIEMgoIAxAAGIAEGKIEMgoIBBAAGIAEGKIEMgcIBRAAGO8F0gEINjY0N2owajeoAgCwAgA&sourceid=chrome&ie=UTF-8


Check Port in Use

    netstat -tulpn | grep ':8000'

Check Process id 

    fuser 8080/tcp

### Commands

Open Vscode

Create Dev Container Python

Install Django

    pip install django

Crete Core app

     django-admin startproject mysite .

Run Server (as test mode)

    python manage.py runserver

Create First App (Poll app)

    python manage.py startapp polls


Create Migrations (as needed)

    python manage.py makemigrations polls

Run Migrations (as needed)

    python manage.py migrate