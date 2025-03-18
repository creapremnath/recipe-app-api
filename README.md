# recipe-app-api

Recipe app API using Django REST Framework

docker build .
docker-compose build

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose up

#For any error

docker-compose down

#to run the tests

# --rm removes the container after execution

docker-compose run --rm app sh -c "python manage.py test"

#Create new app

docker-compose run --rm app sh -c "python manage.py startapp newapp"

# Tutorial going on Implement Recipe filter feature 132 starting
