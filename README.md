# zipmoney

I have used ASP .Net Web Api core and mongodb along with docker



Commands to run a mongodb container

1. docker pull mongo

mongodb image will be downloaded.

2. docker images

3. mkdir -p /mongodata

make a directory to store db data

4. docker run -it -v /data/db:/mongodata --name mongodb -d mongo

5. docker exec -it mongodb bash

6. mongo

7. use zipmoney

8. db
​



Please, find the below commands to run the docker application.

1. open powershell
2. Navigate to the application folder path using CD command
3. Build application in docker
        docker build -t zipapi .
4. Run application
        run -it -p 8080:80 --name myzipapi zipapi
5. Get the list of running containers
        docker ps
