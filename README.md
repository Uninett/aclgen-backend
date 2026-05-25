# aclgen-backend

This is the REST API for the ACLGen web application.

This is a copy of https://github.com/aclgen/aclgen-backend.

## Installing and running ACLGen backend

To install all necessary dependencies run

```console
$ uv pip install -r pyproject.toml
```
To migrate new model changes to the database run

```console
$ python manage.py migrate
```

To run the Django backend, run:

```console
$ python manage.py runserver
```

To run tests run
```console
$ pytest
```

## Swagger

Swagger is available on: http://localhost:8000/swagger/