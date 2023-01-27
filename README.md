# tutorial-on-RESTFul-API-in-flask
This tutorial shows how to create a RESTFul API in Flask With JSON Web Token Authentication and Flask-SQLAlchemy.

## About Project

This project is made using RESTFul API in Flask with JWT and Flask-SQLAlchemey for authentication and authorization and testing is done using Postman. To show the working example of this project I have added the TODO route so if the user is authorized then he can create his todo list.


## Installation
+ Create the folder
+ Create virtual environment

  ``` virtualenv -p python3 .venv ```

+ Activate Virtual environment

  ``` .venv/Scripts/activate ```
  
+ Install flask

  ``` python -m pip install flask ```

+ Create file called requirements.txt which consists following packages
  
  ```
  Flask-RESTful==0.3.8
  PyJWT==1.7.1
  Flask-SQLAlchemy==2.
  ```
+ Install the packages

  ``` pip install -r requirements.txt ```
 

## Start server
Create a new file called api.py

In api.py, the Flask application is initialized and configured. The API resources also set up.

This file is the entry point to the REST API.

You can start server with :

``` python api.py ```

## Database Creation
+ Open terminal
+ Go to Python Shell

  ``` python ```
+ from api import app, db
+ app.app_context().push()
+ db.create_all()
+ exit()
+ Go to Sqlite3

  ``` sqlite3 todo.db ```
  
  note: Here todo.db is the database file name.
+ Check for tables

  ``` .tables ```
+ .exit

## Demo Link
https://drive.google.com/file/d/1-tfoHhshwsbdkIgXpjGj7C5nfyJkFUCi/view?usp=share_link









