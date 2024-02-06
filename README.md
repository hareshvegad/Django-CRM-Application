# Django CRM Application

Overview

This is a Django-based CRM (Customer Relationship Management) application that allows users to manage and organize records of individuals. It includes features for user registration, authentication, record creation, updating, viewing, and deletion.

Table of Contents

    Installation
    Usage
    Features
    File Structure
    Contributing
    License

Installation

    Clone the repository:

bash

git clone https://github.com/hareshvegad/Django-CRM-Application.git

    Change into the project directory:

bash

cd django-crm-application

    Create a virtual environment:

bash

python -m venv venv

    Activate the virtual environment:

        On Windows:

        bash

venv\Scripts\activate

On macOS and Linux:

bash

        source venv/bin/activate

    Install dependencies:

bash

pip install -r requirements.txt

    Apply database migrations:

bash

python manage.py migrate

    Create a superuser account:

bash

python manage.py createsuperuser

    Start the development server:

bash

python manage.py runserver

Visit http://127.0.0.1:8000/ in your browser to access the application.
Usage

    Register a new user account.
    Log in with your credentials.
    Explore the dashboard to manage records.
    Create, update, view, and delete individual records.

Features

    User authentication and authorization.
    CRUD (Create, Read, Update, Delete) operations on records.
    Responsive dashboard for managing records.

File Structure

    crm_application/: Django project settings.
    webapp/: Django app containing models, views, templates, and forms.
    templates/: HTML templates for rendering views.
    static/: Static files such as CSS, JavaScript, and images.

Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Follow the Contributing Guidelines.
License

This project is licensed under the MIT License.