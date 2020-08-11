# Django Demo Project

## myapp

- myapp is created and added to the installed apps
- template folder contains the html file to serve with views.py
- sample model of post in models.py with two fields title and body
- model is imported in views.py and passed to index.html
- in **index.html** for loop is used on posts and same is displayed on when loaded the url(_template with python_)

## Usage

- start the app `python manage.py runserver 0.0.0.0:8000`
- open url [localhost:8000](http://localhost:8000)
- you will see a page that is generated from index.html and models.py Post class
