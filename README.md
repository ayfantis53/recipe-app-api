# recipe-app-api
recipe app api source code

//////////////TERMINAL COMMANDS//////////////
    CLONING FROM GITHUB
      $git clone gitgithub.comlink

    OPENING ATOM
      $atom .

    BUILD DOCKER IMAGE
      $docker build .

    BUILD DOCKER-COMPOSE
      $docker-compose build

    RUN APP SHELL DOCKER-COMPOSE
      $docker-compose run app sh -c ""
        -TO INITIALIZE APP FOLDER
              "django-admin.py startproject app ."
        -TO RUN SIMPLE UNIT TESTS
              "python manage.py test"
        -RUNNING FLAKE TOO TO MAKE SURE THERES NO ISSUES WITH CODE
              "&& flake8"
        -CREATING CORE APP FOLDER
              "python manage.py startapp core"
        -MAKE MIGRATIONS FOR DATABASE SETUP
              "python manage.py makemigrations core"

    COMMITING TO GITHUB
      $git add .
      $git commit -a //////git commit -am "MESSAGE"

    COMMITING TO TRAVIS-CI
      $git push origin
//////////////TERMINAL COMMANDS//////////////
