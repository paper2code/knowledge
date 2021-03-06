# [Django](https://www.djangoproject.com/)

## Notes

- Make migration (where `./manage` is a script that wraps over `python manage.py`):
  1. Change model. Add/remove fields etc.
  2. Run `./manage makemigrations` to create migration from changed models. (can run `./manage makemigrations -n <migration-name>` to give it custom name).
  3. Migration file is created. Run `./manage migrate` to apply
- Run tests:
  - `./manage test` = run all tests
  - `./manage test -k path.to.test` = run specific test. can also run some function from the test inside the file with another `.`.
- Migrate down/up: `./manage migrate <app> <migration-number>`
- Make empty migration: `./manage makemigrations --empty <name-of-migration> <app>`

## Links

- [Profiling Django with DTrace and cProfile (2019)](https://wiedi.frubar.net/blog/2019/11/18/django-performance/)
- [Django’s CBVs were a mistake (2012)](https://lukeplant.me.uk/blog/posts/djangos-cbvs-were-a-mistake/)
- [Testing Django Migrations (2019)](https://sobolevn.me/2019/10/testing-django-migrations)
- [HN: Django 3](https://news.ycombinator.com/item?id=21681732)
- [Viewflow](https://github.com/viewflow/viewflow) - Reusable workflow library for Django.
- [cookiecutter-django-rest](https://github.com/agconti/cookiecutter-django-rest) - Build best practiced apis fast with Python3.
- [rules](https://github.com/dfunckt/django-rules) - Awesome Django authorization, without the database.
- [Django REST framework](https://github.com/encode/django-rest-framework) - Awesome web-browsable Web APIs.
- [Awesome Django](https://github.com/wsvincent/awesome-django)
- [Introducing Django (2005)](https://simonwillison.net/2005/Jul/17/django/)
- [Django 3.1 (2020)](https://www.djangoproject.com/weblog/2020/aug/04/django-31-released/) ([HN](https://news.ycombinator.com/item?id=24048046))
- [Surviving Django (if you care about databases) (2020)](https://www.varrazzo.com/blog/2020/07/25/surviving-django/) ([HN](https://news.ycombinator.com/item?id=24074520)) ([Lobsters](https://lobste.rs/s/l7dqrf/surviving_django_if_you_care_about))
- [Django Views — The Right Way](https://spookylukey.github.io/django-views-the-right-way/) - Opinionated guide on how to write views in Django. ([Lobsters](https://lobste.rs/s/4n63nn/django_views_right_way))
- [Django Middleware](https://www.reddit.com/r/django/comments/hms3n6/django_middleware/)
- [Django Async: What's new and what's next? (2020)](https://deepsource.io/blog/django-async-support/) ([HN](https://news.ycombinator.com/item?id=24160608))
- [Django Redis](https://github.com/jazzband/django-redis) - Redis cache backend for Django.
- [Django styleguide](https://github.com/HackSoftware/Django-Styleguide)
- [Deploy Machine Learning Models with Django](https://www.deploymachinelearning.com/) ([Code](https://github.com/pplonski/my_ml_service))
- [Async Views in Django 3.1 (2020)](https://testdriven.io/blog/django-async-views/) ([HN](https://news.ycombinator.com/item?id=24423637))
- [Build a simple Hacker News clone using Django 3 (2020)](https://www.youtube.com/watch?v=292GB6snFYo)
- [Building a Django app with data access control in 30 minutes (2020)](https://www.osohq.com/post/django-access-control) ([Lobsters](https://lobste.rs/s/tpoc8j/building_django_app_with_data_access))
- [Django Waffle](https://github.com/django-waffle/django-waffle) - Feature flipper for Django.
- [Cookiecutter Django](https://github.com/pydanny/cookiecutter-django) - Framework for jump starting production-ready Django projects quickly.
- [SaaS Pegasus](https://www.saaspegasus.com/) - Django-Powered SaaS Template. ([Docs](https://docs.saaspegasus.com/))
