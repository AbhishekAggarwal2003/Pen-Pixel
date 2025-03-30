# Pen-Pixel

## Overview

This is a simple blogging platform built using Django. It allows users to create, read, update, and delete blog posts. The project includes authentication, category-based organization, and a user-friendly interface.

## Features

User authentication (Register, Login, Logout)

Create, edit, and delete blog posts

Categorization of blog posts

Responsive UI

Secure and scalable


## 🚀 Setup/Installation Requirements

Clone the repository in your system first then run the following command

python -m venv env
.\env\Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver


## Access the application at: http://127.0.0.1:8000/


## Project Structure

blogging-platform/
│── myproject/     # Main Django project directory
│── myapp/         # Blog application
│── media/         # Images
│── templates/     # HTML templates
│── static/        # Static files (CSS, JS, images)
│── db.sqlite3     # SQLite database (or MySQL if configured)
│── manage.py      # Django management script


