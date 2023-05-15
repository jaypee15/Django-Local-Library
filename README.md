# Django-Local-Library

This repository contains the code for a Django application that allows users to browse and checkout books from a local library. The application is still under development, but is already functional.

### Features

* Browse books by title, author, or genre
* Checkout books for a period of 2 weeks
* Return books to the library
* View your checkout history
### Requirements
* Python 3.6+
* Django 3.2+
* SQLite 3.26+
## Installation
### Clone the repository

1. Create a virtual environment and activate it

2. Install the dependencies

    `pip install -r requirements.txt`

3. Migrate the database

    `python manage.py makemigrations`  
    `python manage.py migrate`
    
4. Start the development server

    `python manage.py runserver`

### Usage
The application can then be accessed at http://localhost:8000.

### To-Do
* Add more features, such as the ability to add and remove books from the library
* Improve the user interface
* Add more tests
