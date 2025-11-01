# Install Scaffolder with uv

uv venv
source .venv/scripts/activate
uv add django
uv sync

# Install Django

django-admin startproject mysite .
cd mysite/
python manage.py runserver
