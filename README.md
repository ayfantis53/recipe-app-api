# recipe-app-api
recipe app api source code

CLONING FROM GITHUB
  $git clone gitgithub.comlink

OPENING ATOM
  $atom .

BUILD DOCKER IMAGE
  $docker build .

BUILD DOCKER-COMPOSE
  $docker-compose build

RUN APP SHELL DOCKER-COMPOSE
  $docker-compose run app sh -c "django-admin.py startproject app ."

COMMITING TO GITHUB
  $git add .
  $git commit -a //////git commit -am "MESSAGE"

COMMITING TO TRAVIS CI
  $git push origin
