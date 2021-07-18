# Django Bookstore

A project made with Django and Django REST Framework.

Following the instructions of the book [Django for APIs](https://djangoforapis.com/).

## Initial setup

```bash
$ pipenv install
$ pipenv shell
```

## BD setup

```bash
(blog) $ python manage.py migrate
(blog) $ python manage.py createsuperuser
```

## Run local server

[http://127.0.0.1:8000/swagger/](http://127.0.0.1:8000/swagger/)

```bash
(blog) $ python manage.py runserver
```

## Generate API schema

### Static schema

```bash
(blog) $ python manage.py generateschema > openapi-schema.yml
```
