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
(newspaper) $ python manage.py migrate
(newspaper) $ python manage.py createsuperuser
```

## Run local server

```bash
(newspaper) $ python manage.py runserver
```

## Endpoints

| Endpoint | HTTP Verb |
|----------|---------|
| api/v1/ | GET |
| api/v1/:pk/ | GET |
| api/v1/rest-auth/registration | POST |
| api/v1/rest-auth/login | POST |
| api/v1/rest-auth/logout | GET |
| api/v1/rest-auth/password/reset | POST |
| api/v1/rest-auth/password/reset/confirm | POST |
