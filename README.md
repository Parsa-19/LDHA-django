## Installation

Your system must have [docker-compose](https://docs.docker.com/compose/install/) to follow along.

```bash
docker-compose build
docker-compose up
```
You would be able to access your server on port 8002

## Usage
stop the container
```bash
docker compose down
```
drop to django shell
```bash
docker compose exec web python manage.py shell
```
