# recipe-app-api

This is the api with django-framework

## Getting Started

### Prerequisites
To run this app, you have to [install python](https://realpython.com/installing-python/)

### Installing

To run this repo successfully, you have to:

install/upgrade a package

`pipenv install <package name>`

install the packages:

`pipenv run pip freeze > requirements.txt`

### Set Environment

check environment variables:

`python3 manage.py shell`

`import os`

`print (os.environ)`

add environment variables:

`os.environ['SECRET_KEY'] = value`

launch the environment:

`pipenv shell`

### Run server 

migrate the database:

`python3 manage.py makemigrations <app name>`

`python3 manage.py migrate `

run the server:

`python3 manage.py runserver`

## Running the tests

`python manage.py test`


## Author:

*  Qi Li
*  This is the project developed following this udemy course: 

   https://www.udemy.com/certificate/UC-bf301dc3-0f49-46d0-895e-c1e418fa4a44/

* If anyone want to check my own python project code, please check: 

   https://github.com/ireland-advisor/Advisor

## Contact:

* https://www.linkedin.com/in/lee-qi/
* www.leeqii.com
