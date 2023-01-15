This is the project with objective to create a login page and the secret key of django will be made hidden


SETUP {
    In cmd:
    mkdir django_login
    cd django_login
    code .

    In VSC:
    Ctrl + Shift + ' //powershell terminal
    python -m venv venv  
    venv\Scripts\activate
    pip install django
    django-admin startproject django_login .  //This is done in django_login folder
    python manage.py runserver
    python manage.py startapp Account }

HIDE DJANGO_KEY {
    make .env file in the location of settings.py
    pip install python-decouple in same location
    and change the settings.py
}