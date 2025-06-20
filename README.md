# Business Manager Web Application

This is a simple web application inspired by Google Business Manager. It allows users to register, log in, and manage a list of businesses.

## Features

- User registration and login
- Add, view, and delete businesses

## Requirements

- Python 3.8+
- Flask
- Flask-Login
- Flask-SQLAlchemy

## Setup

1. Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the application:

```bash
flask run --app app.py
```

The app will be available at `http://127.0.0.1:5000/`.
