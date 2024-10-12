## COMMAND NOTES:
     $ docker run --name mongo -d mongo

     $ docker ps

     $ docker top mongo

     $ docker container run -p 80:80 -d --name nginx nginx

     $ docker run -p 3307:3306 -d --name mysql -e MYSQL_RANDOM_ROOT_PASSWORD=yes mysql

     $ docker container logs mysql

     $ docker run -p 8080:80 -d --name apache httpd

     $ docker container ls

     $ docker container stop nginx apache mysql

     $ docker container rm mysql apache nginx

     $ docker container top

     $ docker container inspect

     $ docker container stats

     $ docker container run -it --name proxy nginx bash

     $ docker container run -it --name ubuntu ubuntu

     $ docker container start -ai ubuntu
