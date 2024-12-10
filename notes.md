1. __init__.py file is used to mark a directory as a Python package.
2. asgi.py
   Configures Django for ASGI (Asynchronous Server Gateway Interface), allowing for asynchronous communication and real-time features.
3. wsgi.py
   Configures Django for WSGI (Web Server Gateway Interface), used for deploying the application to production servers.
4. static/
   This directory is used to store static files like CSS, JavaScript, and images that are served to the client. and some other info too
5.  urls.py
    This file is used to define URL patterns for your project or app. It maps URLs to their corresponding views.
6. manage.py
   A command-line utility for managing your Django project. It can be used to run the development server, create migrations, interact with the database, and more.
7. settings.py
   This file contains the configuration for your Django project, including database settings, middleware, installed apps, templates, and more.






// now Im goinf to start my blog app with this django
cmd :- python .\manage.py startapp


1. views.py
Contains the logic for handling requests and returning responses. Views act as the middle layer between the templates and the models.
2. models.py
   Defines the structure of your database tables using Django's Object-Relational Mapping (ORM). Each model corresponds to a table in the database.
3. apps.py
   Contains configuration for the app. Django uses this file to register the app and provide app-specific metadata.
4. admin.py
   Used to register models with the Django admin site and customize their display in the admin interface.
5. tests.py
   Contains test cases for your app to ensure functionality works as expected.
6. 


