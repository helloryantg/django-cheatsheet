# django-cheatsheet

## How to create a new Django project
```bash
django-admin startproject <projectname>
```
## How to start the Django development server
```bash
python3 manage.py runserver
```

## How to stop Django server
```bash
ctrl + C
```

## How to create a new application in the project
```bash
python3 manage.py startapp main_app
```

## Django Directory Structure
```bash
djangoproject
 |
 |-djangoproject
 |  |
 |  |- settings.py: Main settings for project (db, apps, config, etc.)
 |  |- urls.py: Main URLs for entire project
 |
 |- application_name
 |  |- static: (dir) Holds all static files (css, js, images, aux, forms)
 |  |- templates: (dir) Holds all HTML template files
 |  |- migrations: (dir) This holds all data migration files
 |  |- admin.py: This is where we register data models
 |  |- models.py: This is where we put all data models
 |  |- views.py: This is where we put the functions that run our routes
 |  |- urls.py: Every URL for our site is defined here
 |
 |- manage.py: Let's us manage everything about our project
```
