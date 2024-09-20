This is a [Django](https://www.djangoproject.com/) project. [Django](https://www.djangoproject.com/) is a high-level Python web framework

## Getting Started

### How to install Django
1. Install Python

   Get the latest version of [Python](https://www.python.org/downloads/).
3. Install [pip](https://pip.pypa.io/en/stable/).

   The easiest is to use the [standalone pip installer](https://pip.pypa.io/en/latest/installation/).

5. Create Virtual Environment.
   
    This tool provides isolated Python environments, which are more practical than installing
    packages systemwide. It also allows installing packages without administrator privileges.

   Create venv
  
    ```python
    python3 -m venv ilm_books_venv
    ```

    Activate venv
  
    ```python
    source ilm_books_venv/bin/activate
    ```
6. Install Django
  
    ```python
    pip install django
    ```

For more details check [Documentation](https://docs.djangoproject.com/en/5.1/topics/install/).

## Creating a project

  From the command line, **cd** into a directory where you’d like to store your code, then run the following command:

  ```python
  django-admin startproject ilm_books .
  ```

  Run local development server
  
  ```python
  python3 manage.py runserver
  ```
## Create an app

  ```python
  python3 manage.py startapp ilm
  ```
