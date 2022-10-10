# djangochat_realtime

A simple, django chat application that can be used in realtime to chat with anyone!

This application is built with the following:

1. Django Framework
2. JavaScript - AJAX
3. CSS

How to locally develop:

1. Build virtual environment at root directory
    - pip install virtualenv (if haven't already)
    - python -m venv <virtual-environment-name> (ex.  python -m venv env)
    - env/Scripts/activate.bat (Windows) | source env/bin/activate (Mac)
    - Control + Shift + P to select Python Interpretor 
    - Control + Shift + ` to create new bash/powershell terminal
    - Virtual environment activated and ready to go!

2. Within activated virtual env:
    - pip install Django
    - python manage.py makemigrations
    - python manage.py migrate
    - python manage.py runserver 

Have fun!