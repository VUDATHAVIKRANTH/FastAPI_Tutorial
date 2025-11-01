### Connecting DB with Postgresql

Installing postgresql with docker
  1. pull the docker image
     ~~~
     docker pull postgres
  2. run the container
     ~~~
     docker run --name postgres-cont -e POSTGRES_PASSWORD=admin -p 5432:5432 -d postgres
  3. starting the container
     ~~~
     docker ps
     ~~~
     list all the containers that are running
     ~~~
     docker exec -it <dockerid> sh
     ~~~
  4. starting psql
     ~~~
     psql -U postgres
     ~~~
  5. connect to vs code by using extension SQLtool or postgresl and make a new connection
