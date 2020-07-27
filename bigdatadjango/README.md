# django-static-template

[![Build Status](https://travis-ci.org/leogregianin/django-static-template.svg)](https://travis-ci.org/leogregianin/django-static-template)
[![codecov](https://codecov.io/gh/leogregianin/django-static-template/branch/master/graph/badge.svg)](https://codecov.io/gh/leogregianin/django-static-template)
[![GitHub issues](https://img.shields.io/github/issues/leogregianin/django-static-template.svg)](https://github.com/leogregianin/django-static-template/issues)
[![GitHub forks](https://img.shields.io/github/forks/leogregianin/django-static-template.svg)](https://github.com/leogregianin/django-static-template/network)
[![GitHub stars](https://img.shields.io/github/stars/leogregianin/django-static-template.svg)](https://github.com/leogregianin/django-static-template/stargazers)
[![GitHub license](https://img.shields.io/github/license/leogregianin/django-static-template.svg)](https://github.com/leogregianin/django-static-template)


About
-------------------
```django-static-template``` is a template to build static websites made with python django framework.


Install
-------------------
  * Install Python >= 3.x
  * Install dependencies (django >=1.9, <2)
  
```bash
$ pip install -r requirements.txt
```


Run in virtual environments
-------------------

```bash
virtualenv venv -p C:\Python36\python.exe
cd venv
cd Scripts
.\activate
```


Build and run
-------------------
```bash
$ (env) python .\manage.py createsuperuser
$ (env) python .\manage.py migrate
$ (env) python .\manage.py runserver
```

Open browser: 127.0.0.1:8000

Tests
-------------------

```bash
$ (env) python .\manage.py test
```
