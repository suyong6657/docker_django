# docker_django
django, postgresql, nginx


1. Django v2.1
2. Docker v18.06.1
3. Python v3.7


Project Setup

- pipe installed, start by create a new Django Project

<pre><code>
$ mkdir django-on-docker && cd django-on-docker
$ mkdir app && cd app 
$ pipenv install django==2.1
$ pipenv shell <br>
(django-on-docker)$ django-admin.py startproject [project_name] . 
(django-on-docker)$ python manage.py migrate 
(django-on-docker)$ python manage.py runserver
</code></pre>


next, added dockerizing information URL

<https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/#nginx>
