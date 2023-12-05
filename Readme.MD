https://documenter.getpostman.com/view/28628748/2s9YeLYpWZ



### Setup
1. Create a folder and put all the files inside it.
2. Create a virtual environtment - `virtualenv env`
3. Activate VirtualENV - ubuntu : `source env/bin/activate` || windows : `. .\env\Scripts\activate`
4. Run requirements.txt - `pip install -r requirements.txt`
5. Run the Application - `python manage.py runserver`
6. Migrate

**Steps to run application**

1. python -m venv **venv**
2. *venv\Scripts\activate*
3. pip install -r **requirements.txt**
4. python manage.py runserver
-- Omkar Sutar --



# Simple Ecommerce

An extremely simple ecommerce application written in Django.

To install the project follow these steps:

1. `git clone https://github.com/overiq/simple_ecommerce.git`.
1. `cd simple_ecommerce`
1. `virtualenv env`
1. `source env/bin/activate` (for Linux/Mac OS ) or `env\Scripts\activate.bat` (for Windows)
1. `pip install -r requirements.txt`
1. `cd django_project/`
1. `python manage.py migrate`
1. `python manage.py runserver`



# Vendor Management System API

Welcome to the Vendor Management System API, a Django project for managing vendors, purchase orders, and performance metrics.

## Project Overview

The Vendor Management System provides a set of RESTful APIs for user authentication, vendor management, purchase order creation, and performance metric tracking. It is designed to streamline the process of handling vendors and purchase orders.

## Features

- User Signup and Login
- Vendor Management
- Purchase Order Creation and Management
- Performance Metrics Tracking

## Project Structure

The project structure follows common Django conventions:

- `vendor_management_system/`: Django project directory
  - `Vendor/`: Django app containing API views, serializers, and models
  - `manage.py`: Django management script
  - `requirements.txt`: Project dependencies
  - `README.md`: Project documentation

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/omkarsutar1255/My-Django-Projects.git


2. `cd vendor-management-system`
3. `python -m venv venv`
4. `venv\Scripts\activate`
5. `pip install -r requirements.txt`
6. `python manage.py migrate`
7. `python manage.py runserver`

The API will be accessible at `http://127.0.0.1:8000/`.

API Documentation
API documentation is available `https://documenter.getpostman.com/view/28628748/2s9YeLYpWZ`.
Access the admin interface at `http://127.0.0.1:8000/admin/`.
