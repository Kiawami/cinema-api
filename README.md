# Cinema API

Cinema API service on Django REST Framework

## Installing

Install PostgeSQL and create database using commands:

```
git clone https://github.com/4ndyua/cinema-api.git
cd cinema-api
python -m venv venv
venv/scripts/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py runserver
```

### Running Docker:

Use commands:
```
docker-compose build
docker-compose up
```


### Features

