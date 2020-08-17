
==============
Install Python
==============

I am using MAC machine so basically, I downloaded the .dmg package and installed it on my machine. 
you can download and install Docker from this link - (https://docs.docker.com/desktop/)

Install Django
==============

Download latest version of Python from (https://www.python.org/downloads/mac-osx/)

Demo 1
======

Run these commands on the terminal.

Create a virtual environment first with the below-given command

.. Note::
   
    the dot at the end in the below command means the current directory::

.. code-block:: sh

    virtualenv -p python3 .

Now activate the environment::

    source bin/activate

To deactivate::

    source bin/dactivate

Use these commands to check what all stuff has been installed in your virtual environment::

    pip freeze

To install any package::

    pip install django==3.0.5

To create the project::

    django-admin.py startproject my_project .

To Run the server::

    python3 manage.py runserver

To create an app, the command is::

    python3 manage.py startapp my_app

To make a migration file::

    python manage.py makemigrations

To migrate to the database::

    python manage.py migrate

MODELS
======

Models in python are a class which represent a table in a database
Each type of data we have (e.g Articles, Users) is represented by its own model
Each model maps to a single table in a database
ORM commands::

    from Articles2.models import Articles

    Articles.save()

    Articles.objects.all()

    Articles.title

    Articles.objects.all()[0].title

Admin page
==========

Reset the admin portal password.

First, create a new user::

    python3 manage.py createsuperuser