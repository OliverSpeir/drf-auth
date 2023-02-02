# LAB - 33

## Project: Lab Name

### Author: Oliver Speir

### Description

- Django Rest Framework API with JWT Authorization for Authenticated Users
- WhiteNoise Static File Creation
- Docker Containers run with Green Unicorn Production Server
- Docker Container creates static files and migrates DB which creates default superuser on start up

### Setup

Run:
- clone and cd into directory
- `docker compose up`
- superuser will be auto set to username: dev password: dev

Test:
- send POST requests to `127.0.0.1:8000/api/token/`
  - `{"username": "dev", "password": "dev"}` in body
    - this will confirm that JWT features are functioning correctly
- `docker-compose run web python manage.py test`
  - while docker container is running 
### Resources

- [Django REST Framework](https://www.django-rest-framework.org/)
- [Docker](https://www.docker.com/)
- [postgresql](https://www.postgresql.org/)
- [Green Unicorn (gunicorn)](https://gunicorn.org/)
- [WhiteNoise](https://whitenoise.evans.io/en/latest/)