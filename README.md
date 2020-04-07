# drf-demo

A project for article at some_href


1. clone the project 
2. go to root directory
3. then run "pip install -r requirements.txt"
4. python project/manage.py makemigrations core
5. python project/manage.py migrate core
6. change project/conf/base.py ALLOWED_HOSTS = ['localhost']
7. python project/manage.py runserver
8. then open browser and navigate to "http://localhost:8000/api or http://localhost:8000/admin"