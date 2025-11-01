#Create Scaffolder with uv

_uv venv_  
_source .venv/scripts/activate_

#Install Django
_uv add django_
_uv sync_
_django-admin startproject ._
_python manage.py runserver_

#Create App Task
_python manage.py startapp tasks_
