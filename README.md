# template-django-mysql-dockercompose
This is my template for `Django 2.x and MySql 5.7`  with `docker-compose` .

# Setup

```sh
# start
$ docker-compose up -d --build

# stop and remove container
$ docker-compose down

# for /admin setup
$ docker-compose run --rm web python manage.py migrate
$ docker-compose run --rm web python manage.py createsuperuser
```
