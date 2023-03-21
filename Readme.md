# LEARNING DJANGO

> By: DANIEL GITHIOMI

A repository created to help me document topics and content of the Python Django Framework. It also contains a sample project created using the same.

## DJANGO BACKGROUND

* Django is a high level python web development framework that encourages rapid development and pragmatic design
* A framework is a collection of tools in one package that makes development easier.
* Django has the following features:

    * Object-Relational mapping
    * URL Routing
    * HTML Templating
    * Form Handling
    * Unit testing

## CREATING A PYTHON PROJECT

Navigate to the directory of choice and run the command:

```
    django-admin startproject <name-of-the-project>
```

This creates a folder that contains:

* A **manage.py** file -> Used to run python commands
* A folder with the name of the project that also contains .py files

    * __\_\_init\_\_.py__ -> Tell python that the folder contains python code (dunder init)
    * __wsgi.py__ and __asgi.py__  -> Provide hooks for webservers
    * __setting.py__ -> Configures the django project
    * __urls.py__ -> Handles routing within the project

A project can be run by running the following command in the right directory that will run on **localhost:8000**

```
    python manage.py runserver
```

## DJANGO APPS

This is a component within the overall django project that has a set of python files to accomplish a specific purpose using features

Each of these features are put into different components (apps).

To create a new app/component, use the following command:

```
    python manage.py startapp <name-of-the-app>
```
