# Django-LocationApp

[![](https://img.shields.io/badge/Made_with-Python3-blue?style=for-the-badge&logo=python)](https://www.python.org "Python3")[![](https://img.shields.io/badge/Made_with-Django-blue?style=for-the-badge&logo=django)](https://www.djangoproject.com/ "Django")

</p>

## Description

This application would list the nearby shops closer to the user’s location. The location-based web apps in Django by using its sub-framework known as GeoDjango is to be made.

        ----------------------------------------------------------------------------------------

#### Software Requirements

Python3
OSGeo4w

#### Installation

Install the dependencies by running:
```html  
    pip install psycopg2-binary
```

#### Run using Command Prompt

Navigate to the nearbyshops folder which has manage.py file then run the following command on cmd

```html
docker run --name=postgis -d -e POSTGRES_USER=user001 -e POSTGRES_PASS=123456789 -e POSTGRES_DBNAME=gis -p 5432:5432 kartoza/postgis
python manage.py runserver
```

### Tech stack

`Backend` : Python3 <br>
`Framework` : Django <br>
`Database` : PostgreSQL <br>
`Frontend` : Html <br>

