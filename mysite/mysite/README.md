# About Django Files

* The inner mysite/ directory is the actual Python package for your 
project. 
Its name is the Python package name you’ll need to use to import anything 
inside it (e.g. mysite.urls).

* mysite/__init__.py: An empty file that tells Python that this directory 
should be considered a Python package. If you’re a Python beginner, read 
more about packages in the official Python docs.

* mysite/settings.py: Settings/configuration for this Django project. 
Django 
settings will tell you all about how settings work.

* mysite/urls.py: The URL declarations for this Django project; a “table 
of 
contents” of your Django-powered site. You can read more about URLs in URL 
dispatcher.

* mysite/asgi.py: An entry-point for ASGI-compatible web servers to serve 
your project. See How to deploy with ASGI for more details.

* mysite/wsgi.py: An entry-point for WSGI-compatible web servers to serve 
your project. See How to deploy with WSGI for more details.
