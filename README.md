# LAB - 33

## Project: Lab Name

### Author: Oliver Speir

### Description

Added DRF JWT
Added green unicorn production server

### Setup

to run:
- `docker compose up`
- superuser will be auto set to username: dev password: dev
test:
- can send POST requests to `127.0.0.1:8000/api/token/`
  - `{"username": "dev", "password": "dev"}` in body
    - this will confirm that JWT features are functioning correctly

### Resources

- [Django REST Framework](https://www.django-rest-framework.org/)
- [Docker](https://www.docker.com/)
- [postgresql](https://www.postgresql.org/)
