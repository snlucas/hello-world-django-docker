# hello-world-django-docker
A simple hello, world made in Django and containerized with Docker.

## Commands
```sh
$ sudo docker-compose run web django-admin startproject hello_world_django_docker .
$ sudo chown -R $USER:$USER .
$ docker-compose up
$ docker ps
$ # Get image ID to start a new process
$ # Start bash inside image
$ docker exec -it <Image ID> bash
$ python manage.py migrate
$ python manage.py createsuperuser
```

