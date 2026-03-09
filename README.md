[![Build Status](https://app.travis-ci.com/ananya1806/swe1-app.svg?branch=main)](https://app.travis-ci.com/ananya1806/swe1-app)
[![Coverage Status](https://coveralls.io/repos/github/ananya1806/swe1-app/badge.svg?branch=main)](https://coveralls.io/github/ananya1806/swe1-app?branch=main)

# SWE1 Django Polls App

![Build Status](https://travis-ci.com/ananya1806/swe1-app.svg?branch=main)
![Coverage Status](https://coveralls.io/repos/github/ananya1806/swe1-app/badge.svg?branch=main)

## Overview

This project is a Django **Polls web application** built using the official Django tutorial.
It includes a CI/CD pipeline with automated testing, linting, formatting checks, and deployment.

Live App:
http://django-env.eba-gpemsgbr.us-east-1.elasticbeanstalk.com/polls/

## Features

* Django Polls application
* Continuous Integration using **Travis CI**
* Code formatting check with **Black**
* Linting with **Flake8**
* Test coverage using **coverage.py** and **Coveralls**
* Automatic deployment to **AWS Elastic Beanstalk**

## Run Locally

Install dependencies:

```
pip install -r requirements.txt
```

Run migrations and start server:

```
python manage.py migrate
python manage.py runserver
```

## Tests

Run tests with coverage:

```
coverage run manage.py test
coverage report
```

## Deployment

The app is automatically deployed to **AWS Elastic Beanstalk** after successful Travis CI builds.

## Author

Ananya Singh

