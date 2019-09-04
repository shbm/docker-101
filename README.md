docker build -t shbm/node-web-app .

docker images

docker run -p 49160:8080 -d shbm/node-web-app

docker ps

docker logs <container id>

docker exec -it <container-id> /bin/bash

docker ps

CHEAT SHEET:
https://github.com/wsargent/docker-cheat-sheet

For Python:
https://runnable.com/docker/python/dockerize-your-python-application

For NodeJS:
https://nodejs.org/de/docs/guides/nodejs-docker-webapp/

For JAVA:
https://stackify.com/guide-docker-java/
