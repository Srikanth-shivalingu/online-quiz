# Online Quiz web Application

A web-based online quiz application built with Django that allows users to take quizzes, view results, and manage courses. The application features a user-friendly interface, robust functionality, and a flexible design.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)

## Features

- User registration and authentication
- Course creation and management
- Question management for each course
- Automatic grading of quizzes
- Display of user results and overall performance
- Responsive design for mobile and desktop devices
## Usage
Register for an account to start taking quizzes.
Navigate through the courses and attempt available quizzes.
View your results and overall performance in the dashboard.

## Project Structure

- **online_quizz/**
  - **online_quizz/**
    - `__init__.py`
    - `settings.py`
    - `urls.py`
    - `wsgi.py`
  - **quizzes/**
    - `__init__.py`
    - `admin.py`
    - `apps.py`
    - `models.py`
    - `tests.py`
    - `views.py`
    - **migrations/**
      - `__init__.py`
  - **templates/**
    - **online_quizz/**
      - `base.html`
      - `course_detail.html`
      - `register.html`
      - `login.html`
      - `result.html`
      - `teacher_view.html`
  - **static/**
    - **css/**
    - **js/**
    - **images/**
- `manage.py`
- `requirements.txt`



## Technologies Used
- Django: Web framework for Python.
- HTML/CSS , Bootstrap: Markup and styling.
- JavaScript: For dynamic features.
- SQLite: Database for development.
