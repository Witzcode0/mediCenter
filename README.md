# mediCenter
mediCenter

1] create repository in github

2] clon your created repo in your local system
>>> git clone https://github.com/Witzcode0/mediCenter.git

3] cd mediCenter
your-path\mediCenter>

4] Create virtual environment
your-path\mediCenter> python -m venv [env_name]

5] Activate/Deactivate your virtual env.
your-path\mediCenter> [env_name]\Scripts\activate
your-path\mediCenter> [env_name]\Scripts\deactivate

([env_name]) yout-path\mediCenter>

6] make sure you have installed python

Django 3.x series: Requires Python 3.6, 3.7, 3.8, or 3.9.
Django 2.x series: Requires Python 3.5, 3.6, 3.7, or 3.8.
Django 1.11.x series: Supports Python 2.7, as well as Python 3.4, 3.5, 3.6, and 3.7 (starting from Django 1.11.17).

([env_name]) yout-path\mediCenter> python --version
Python 3.12.0

7] install Django(make sure your virtual is activated)
([env_name]) yout-path\mediCenter> pip install django

([env_name]) yout-path\mediCenter> python
Python 3.12.0 (tags/v3.12.0:0fb18b0, Oct  2 2023, 13:03:39) [MSC v.1935 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> import django
>>> print(django.get_version())
5.0.4

8] Check your installed module and package in virtual env.
([env_name]) yout-path\mediCenter> pip list
Package  Version
-------- -------
asgiref  3.8.1
Django   5.0.4
pip      24.0
sqlparse 0.4.4
tzdata   2024.1

9] create requirements.txt in your base dir
([env_name]) yout-path\mediCenter> type nul > requirements.txt

10] Add your installed modules and packages in requirements.txt file
([env_name]) yout-path\mediCenter> pip freeze > requirements.txt

11] Install module and package from requirements.txt file
([env_name]) yout-path\mediCenter>` pip install -r requirements.txt`

12] Creating a project
([env_name]) yout-path\mediCenter> django-admin startproject [project_name] .

13] Creating the app
([env_name]) yout-path\mediCenter> python manage.py startapp [app_name]