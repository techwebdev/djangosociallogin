## Installation 
- install python3 and pip3 
- then install virtualenv 
- create virtualenv and activate the virtualenv 
- install django on virtualenv

## setup command 
- `pip3 install virtualenv` or `pip install virtualenv` install virtualenv  
- `virtualenv venv`  create virtualenv called venv 
- default this activated usign `deactivated` to deactive venv 
- active again write  in ubuntu `source venv/bin/activate` or Windows `venv/Scripts/activate`
- create djagno project using ` django startproject nameofproject`
- going to project using `cd nameofproject` and  create django application using `django startapp nameofapp` or `python3 manage.py startapp nameofapp` or `python manage.py startapp nameofapp`
- run makemigration and migrate using `python3 manage.py makemigrations` and `python3 manage.py migrate` or `python manage.py makemigrations` and `python manage.py migrate`
- run server using `python3 manage.py runserver` or `python manage.py runserver`

#### Note:- 
if you use widnows then no need to write python3 in windows only write python 
all `python` command use in windows
