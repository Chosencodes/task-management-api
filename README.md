# Task Management API

Simple Task Management API built with Django and Django REST Framework.

## Features
- User registration & JWT authentication
- Create/read/update/delete tasks
- Toggle task complete/incomplete
- Per-user task ownership

## Tech
- Django
- Django REST Framework
- djangorestframework-simplejwt
- django-cors-headers

## Install & Run (development)
1. Clone repo
2. Create venv & install deps:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
