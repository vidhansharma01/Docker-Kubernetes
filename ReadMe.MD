//To show the process pull by docker
docker ps -a

//to give interactive node console
docker run -it node

//to build docker file
docker build .

//stop docker container
docker stop containerName

//run an image 
docker run -p 3000:80 imageSHA

//restart a container
docker start containerName

//currently running container
docker ps

//interactive console in docker
docker run -it imageSHA

//removing docker container
docker rm containerName

//docker images on hard drive
docker images

//remove images
docker rmi imageSHA

//inspecting docker images
docker image inspect imgSHA

//coping files into & from container
docker cp FileName/FolderName elastic_merkle:/ts

//naming docker image
docker build -t name:tag .

//pushing to docker hub
docker push imageTAG

//pulling image file from docker hub
docker pull node

//to get the volume stored locally
docker volume ls

//Volume command in docker
docker run -d --rm -p 3000:80 --name feed-app -v feedback:/app/feedback
 -v "/users/../folderName" -v /app/node_modules feed:volumes

//For container communicating with localhost
host.docker.internal

//To get details of container
docker container inspect containerName

//Network 
docker network create networkName

//connecting a container to a network
docker run -d --name mongodb --network favorites-network mongo

//starting docker-compose
docker-compose up -d
docker-compose down
