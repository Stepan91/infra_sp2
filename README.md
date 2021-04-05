# YaMDB 
Is the base of user reviews about movies, books, music.
This is a REST API for it.

Stack: Python 3, Django 3.0.5, Django Rest Framework, SQlite3, GIT, gunicorn, nginx, docker, docker-compose.

# The YAMdb's container

The container contains the backend of a social network service for sharing impressions of movies, music and books

## Installing

To deploy this container you need to:
1. Create a container based on Dockerfile and docker-compose.yaml with the command 'docker-compose up'
2. Check the container you created in a separate terminal window with the command 'docker ps -a'
3. Go to the terminal interface with the command 'docker exec -it api_yamdb_web_1 bash'
4. Make migrations with the command 'python manage.py migrate'
5. Create administrator with the command 'createsuperuser'
6. To fill the database with initial data, when the container is running, go to 'localhost: 8000/admin' in the browser, enter the administrator login and password

## Authors

* **Stepan Pryn** - (https://github.com/Stepan91)
