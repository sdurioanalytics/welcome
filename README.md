# Django's Good Coding Practices (PEP8)

When initiating a work partnership with `SDU RIO Analytics` please follow **[Django’s Coding Style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/)** to match your code against these guidelines. Further reading:
- [Django’s Coding Style](https://docs.djangoproject.com/en/dev/internals/contributing/writing-code/coding-style/)
- [Designing Better Models](https://simpleisbetterthancomplex.com/tips/2018/02/10/django-tip-22-designing-better-models.html)
- [VScode extension cornflakes-linter for flake8](https://marketplace.visualstudio.com/items?itemName=kevinglasson.cornflakes-linter)

#### [How to Use Flake8](https://simpleisbetterthancomplex.com/packages/2016/08/05/flake8.html)

Flake8 is a Python library for checking your code base against coding style (PEP8), programming errors (like “library imported but unused” and “Undefined name”) and to check cyclomatic complexity.

```
flake8 ~/GitHub/sdurioanalytics
```

#### [How to Use isort](https://github.com/timothycrosley/isort#using-isort)

Use isort to automate import sorting, to see the proposed changes without applying them:

```
isort callfinder/PureWebService.py --diff
```


#### SDU RIO Analytics Technical Perimeter as a `requirements.txt` file:

```
Python == 3.8.2
Django == 3.0.6
scikit-learn
```

Css, JS libraries:

```
Bootstrap == 4.4.1
jQuery == 3.4.1
DataTables == 1.10.20
Highcharts JS == 8.0.4
```
