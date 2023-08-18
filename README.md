# docker-commands
docker commands

----------------

docker pull php

docker images

docker run -it --name php_contanar php:7.4-apache /bin/bash

docker ps

docker ps -a

docker stop 466dd0d1cda7  

docker rm 466dd0d1cda7

docker rmi b88c774ecf8a

docker -t php_apache

docker build -t php_apache

docker run -r --rm -p 80:80 -v d:/damp/site/:/var/www/html/ --name php_contanar php_apache

docker-compose up

docker exec -it 2665656566 bash

mysql -uroot -p12345

docker-compose down

wsl --list

wsl --update

wsl --set-default-version 1

wsl --set-default-version 2

wsl -l -v

wsl --install -d Ubuntu

docker run -d -p 80:80 docker/getting-started

docker pull mysql

docker -v

docker pull hello-world

docker search MySql

docker search nginx

docker images

docker run python

docker ps

docker ps -a

docker build -t getting-started

Dockerfile

docker build -t hello-con

docker run --name hello-world hello-con

wsl

cd ~

curl -s "https://laravel.build/laravel-app?with=mysql,redis,selenium" | bash

cd laravel-app

./vendor/bin/sail up -d

./vendor/bin/sail down
code .
