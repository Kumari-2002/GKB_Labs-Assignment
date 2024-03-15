# Django Web Application by using default SQLite3 database
It is a web application built with Django allows users to input data, validate it, store it in an SQLite database, retrieve it, and display it in a tabular format.It provides a simple and intuitive interface for users to input their personal data, including name, email, age, and date of birth. This data is securely stored in an SQLite database and can be easily retrieved and viewed within the application.
## Features
- User-friendly input form with client-side validation for data accuracy.
- Storage of user data in an SQLite database.
- Retrieval of stored user data displayed in a tabular format.
- Easy setup and deployment using Django's built-in development server and SQLite database.
## Getting Started
### Prerequisites
To run this project, you'll need:

- Python 
- Django 
- SQLite3 
#### Solving started

# first open the COMMAND PROMPT and enter below commands
- django-admin startproject project name 
- cd project name
- python manage.py startapp testapp
####   Now, let's define the models, views, forms, and templates for our web application
The code is in the code editor.

After writing the models.py. just do the below commands
# py manage.py makemigrations
# py manage.py migrate

##  Now, let's create the HTML templates:

Before writing the html templates, we can create folders under main project 'templates'. Inside templates 'testapp' folder. inside testapp create Html files what you need.
if you want to add styles then create a folder 'static' under mainproject. inside this add css folder. inside css folder add css files.
### SAMPLE 
Project name
│ manage.py
│
└Project name
│ │ settings.py
│ │ urls.py
│ │ ...
│
└───application app (testapp)
│ models.py
│ forms.py
| admin.py
│ views.py
│
└───templates/
│ index.html
│ retrieve.html

###  Run the Django server

command:

# py manage.py runserver.

After successfully running the command. you got a one url. copy that url and paste in browser. The final output you can see here
