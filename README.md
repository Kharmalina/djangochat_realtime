# Chatify

A simple, django chat application that can be used in realtime to chat with anyone!

This application is built with the following:

1. Django Framework
2. AJAX
3. jQuery
4. CSS

Features
    - Choose a room name and chat with multiple people or one on one (as long as room name is the same)
    - Accurate realtime timestamps of messages 

How to locally develop:

    Build virtual environment at root directory
        - pip install virtualenv (if haven't already)
        - python -m venv <virtual-environment-name> (ex.  python -m venv env)
        - env/Scripts/activate.bat (Windows) | source env/bin/activate (Mac)
        - Control + Shift + P to select Python Interpretor 
        - Control + Shift + ` to create new bash/powershell terminal
        - Virtual environment activated and ready to go!

    Within activated virtual env:
        - pip install Django
        - python manage.py makemigrations
        - python manage.py migrate
        - python manage.py runserver 

While using Chatify:
    - make sure the Room Name is spelled correctly - if not you will be in the wrong room