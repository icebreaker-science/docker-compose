# Icebreaker Docker-Compose

This docker-compose definition provides a simple way to start the whole system - a database, the backend and the frontend.

How to use it:

1. Clone this repository.
2. In the case of production: Create a `docker-compose.override.yml` file, overwrite at least the database password and the JWT secret and use the `production` tag of the images.
3. Run `docker-compose up`.

The website is now available at http://localhost:12100 and the backend server is hosted at http://localhost:12100/api/.
