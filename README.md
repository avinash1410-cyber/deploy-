# Heroku Deployment Example

A minimal Django project which shows a page with current date and time.

Check out:

* Explainer video: https://youtu.be/hu99aiU0tIA

## Setup

Use the pipenv tool

``` shellsession
$ pip install pipenv
$ cd <proj-dir>
$ pipenv install
```

Now you need to enter the pipenv shell to run the examples:

``` shellsession
$ pipenv shell
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py runserver
```

Next follow the video to understand the code and deploy.
