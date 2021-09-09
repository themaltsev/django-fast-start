# django-fast-start

открывает созданую папку с проектом VS code

Ставим venv

pip install --upgrade pip

pip install django

python -m venv venv

активируем виртуалку

source venv/Scripts/activate

pip install django

django-admin startproject "Name-project"

cd "Name-project"

python manage.py runserver

#Mysql

pip install mysqlclient

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql', 
        'NAME': 'django',
        'USER': 'root',
        'PASSWORD': '123',
        'HOST': 'localhost',   
        'PORT': '3306',
    }    
}
#Mysql

#создаём приложение 

python manage.py startapp "name app"

python manage.py makemigrate

python manage.py migrate
