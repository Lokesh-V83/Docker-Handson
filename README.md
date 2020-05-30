**Docker Handson examples**

Sample Spring boot application deployed in Docker container.

Steps to build image:

1. **Docker Build Image** 

   docker build -t somename/applicationname:version .

2. **Docker Run Command**

   docker run -it -d -p 8080:8080 imagename /bin/bash

   Note: If you using alpine os please use /bin/sh

3. **Docker exec command to switch into container**

   docker exec -it containername /bin/sh

   to list the container name use **docker ps** command
