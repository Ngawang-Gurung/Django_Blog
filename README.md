# Django Blog Project

Welcome to the Django Blog Project! This is a simple yet powerful blogging platform built with Django.

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Running the Project](#running-the-project)
- [Creating a Superuser](#creating-a-superuser)
- [Accessing the Application](#accessing-the-application)

## Getting Started

Follow these instructions to get the project up and running on your local machine.

### Installation

1. **Clone the repository**
    ```sh
    git clone https://github.com/Ngawang-Gurung/Django_Blog.git 
    cd django-blog
    ```

2. **Create a virtual environment**
    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment**

    - **Windows**
        ```sh
        venv\Scripts\activate
        ```

    - **macOS/Linux**
        ```sh
        source venv/bin/activate
        ```

4. **Install dependencies**
    ```sh
    pip install -r requirements.txt
    ```

5. **Apply migrations**
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

## Running the Project

Start the development server by running:
```sh
python manage.py runserver
```

## Creating a Superuser

To create a superuser for accessing the Django admin interface, run:
```sh
python manage.py createsuperuser
```
Follow the prompts to set the username, email, and password.

## Accessing the Application

Once the server is running, open your web browser and navigate to:
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

You can access the Django admin interface at:
[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---
