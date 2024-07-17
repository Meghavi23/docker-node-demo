### Build the Docker Image ###
docker build -t demo-node-js .

### Run the Docker Container ###
docker run -p 3000:3000 demo-node-js

### list all running containers ###
docker ps

### stop a running container ###
docker stop <container_id>

### remove a container ###
docker rm <container_id>

### remove an image ###
docker rmi demo-node-js
