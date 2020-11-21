#Get into container

docker exec -it <<container-name>> /bin/bash

#In tomcat directory, go to webapps.dist and execute 

cp -R * ../webapps
