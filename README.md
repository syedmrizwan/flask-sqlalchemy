# flask-sqlalchemy

# Steps to run flask-sqlalchemy  (Dev mode):

## 1. Dependencies:

To be able to run **flask-sqlalchemy** you have to meet following dependencies:

- python3 and pip3
- [Install postgres](https://www.postgresql.org/download/linux/ubuntu/)

## 2. Start Postgres DB:

- `$ su postgres`
- `$ psql`
- `$ create database cars_api`

## 3. Install App Requirements:

- Switch to project root directory.
- run `$ pip3 install -r requirements.txt`


## 4. Run migrations
- Switch to project root directory.
- run `$ python3 manage.py db init`
- run `$ python3 manage.py db migrate`
- run `$ python3 manage.py db upgrade`

## 5. Start Application Server

- `export FLASK_APP=app.py`
- `flask run`

# Creating virtual env for mac and linux

## Creating an environment

``` virtualenv -p python3 <env folder>``` 

i.e 

`virtualenv -p python3 ~/virtual/training` 

## Activating an environment

`source <env directory>/bin/activate`

i.e

`source ~/virtual/training/bin/activate`


## Deactivate

`deactivate`
