# Django GraphQL (using graphene_django) Examples

This is following tutorial on https://docs.graphene-python.org/projects/django/en/latest/tutorial-plain/


# How to run

Install dependencies

```bash
pipenv install
```

Migrate Django

```bash
pipenv run python manage.py migrate
```

Load the fixtures data
```bash
pipenv run python manage.py loaddata ingredients
```

Run django
```bash
pipenv run python manage.py runserver
```

Access GraphiQL Views by opening [localhost:8000/graphql](http://localhost:8000/graphql)

