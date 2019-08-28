docker build -t shbm/node-web-app .

docker images

docker run -p 49160:8080 -d shbm/node-web-app

docker ps

docker logs <container id>

docker exec -it container-id /bin/bash

docker ps

Cheat Sheet: https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes
