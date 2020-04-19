# redis-DjangoRest
This repository contains the code for the assignment.

Getting Started
Prerequisites

Kindly ensure you have the following installed on your machine:

 Python 3
 
 Pipenv
 
 Django RestFramework
 
 Redis
 
 Git
 
 An IDE or Editor of your choice
 
Running the Application

Clone the repository
$ git clone https://github.com/aman030997/redis-DjangoRest.git

Check into the cloned repository

$ cd django_redis_demo

If you are using Pipenv, setup the virtual environment and start it as follows:

$ pipenv install && pipenv shell

Install the requirements

$ pip install -r requirements.txt

Configure Redis configuration in django_redis_demo/settings.py


Start the Django API


$ python manage.py runserver

Send requests to http://localhost:8000/api

and 
http://localhost:8000/<key_name>

Functionalities include:

get value from key

set key-value pair

expire key

get all key-value pairs


