# LAB - 33

## Project: Lab Name

### Author: Oliver Speir

### Description

Added DRF JWT
Added green unicorn production server

### Setup

to run:
- Clone and while in directory run command:
- `docker compose up`
- Open new terminal window and run:
- `docker-compose run web python manage.py migrate`
- `docker-compose run web python manage.py createsuperuser`
- `docker-compose run web python manage.py runserver`

test:
- `docker-compose run web python manage.py test`

### Resources

- [Django REST Framework](https://www.django-rest-framework.org/)
- [Docker](https://www.docker.com/)
- [postgresql](https://www.postgresql.org/)
