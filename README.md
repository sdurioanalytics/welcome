# Django's Good Coding Practices (PEP8)

![🐍 Python webapps-deploy@v2](https://github.com/sdurioanalytics/sdurioanalytics/workflows/%F0%9F%90%8D%20%20Build%20and%20deploy%20Python%20webapps-deploy@v2/badge.svg)
![GitHub Pipenv locked Python version](https://img.shields.io/github/pipenv/locked/python-version/sdurioanalytics/welcome?color=green)
[![Django 3.1.7](https://img.shields.io/badge/Django-3.1.7-green)](https://www.djangoproject.com/weblog/2020/aug/04/django-31-released/)
[![PostgreSQL 12.5](https://img.shields.io/badge/PostgreSQL-12.5-green.svg)](https://www.postgresql.org/docs/12/)
[![License BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](LICENSE)
[![time tracker](https://wakatime.com/badge/github/sdurioanalytics/sdurioanalytics.svg)](https://wakatime.com/badge/github/sdurioanalytics/sdurioanalytics)
[![Follow SDU RIO Analytics on Twitter](https://img.shields.io/twitter/follow/sdurioanalytics.svg?style=social&logo=twitter)](https://twitter.com/sdurioanalytics)
[![Follow JV conseil – Internet Consulting on Twitter](https://img.shields.io/twitter/follow/JVconseil.svg?style=social&logo=twitter)](https://twitter.com/JVconseil)

When initiating a work partnership with `SDU RIO Analytics` please follow **[Django’s Coding Style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/)** to match your code against these guidelines. Further reading:

- [Django’s Coding Style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/)
- [Designing Better Models](https://simpleisbetterthancomplex.com/tips/2018/02/10/django-tip-22-designing-better-models.html)
- [VScode extension cornflakes-linter for flake8](https://marketplace.visualstudio.com/items?itemName=kevinglasson.cornflakes-linter)

#### SDU RIO Analytics Technical Perimeter as a `requirements.txt` file

1. `PostgreSQL v12.5` &nbsp; :arrow_right: &nbsp; `PostgreSQL v12.x`
1. `Django v3.1.7` &nbsp; :arrow_right: &nbsp; `Django v3.1.x`
1. `Python v3.8.8_1` &nbsp; :arrow_right: &nbsp; `Python v3.8.8_1`
1. `Bootstrap v4.6.0` &nbsp; :arrow_right: &nbsp; `Bootstrap v4.6.0`
1. `DataTables v1.10.24` &nbsp; :arrow_right: &nbsp; `DataTables v1.10.24`
1. `Highcharts v9.0.1` &nbsp; :arrow_right: &nbsp; `Highcharts v9.0.1`
1. `jQuery v3.6.0` &nbsp; :arrow_right: &nbsp; `jQuery v3.6.0`
1. `PURE Api v5.19` &nbsp; :arrow_right: &nbsp; `PURE Api v5.19`
1. `work_mem 8192` Azure Database for PostgreSQL server parameters `none`

#### [How to Use Flake8](https://simpleisbetterthancomplex.com/packages/2016/08/05/flake8.html)

Flake8 is a Python library for checking your code base against coding style (PEP8), programming errors (like “library imported but unused” and “Undefined name”) and to check cyclomatic complexity.

```bash
flake8 ~/GitHub/sdurioanalytics
```

#### [How to Use isort](https://github.com/timothycrosley/isort#using-isort)

Use isort to automate import sorting, to see the proposed changes without applying them:

```bash
isort callfinder/PureWebService.py --diff
```

#### SDU Styling Guide

- [SDU Brandguide](http://anygivenmonday.org/clients/sdu/brandguide/#farver)
