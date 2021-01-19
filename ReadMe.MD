**To show the process pull by docker**

:whale: docker ps -a

**to give interactive node console**

:whale: docker run -it node

**to build docker file**

:whale: docker build .

**stop docker container**

:whale: docker stop containerName

**run an image**

:whale: docker run -p 3000:80 imageSHA

**restart a container**

:whale: docker start containerName

**currently running container**

:whale: docker ps

**interactive console in docker**

:whale: docker run -it imageSHA

**removing docker container**

:whale: docker rm containerName

**docker images on hard drive**

:whale: docker images

**remove images**

:whale: docker rmi imageSHA

**inspecting docker images**

:whale: docker image inspect imgSHA

**coping files into & from container**

:whale: docker cp FileName/FolderName elastic_merkle:/ts

**naming docker image**

:whale: docker build -t name:tag .

**pushing to docker hub**

:whale: docker push imageTAG

**pulling image file from docker hub**

:whale: docker pull node

**to get the volume stored locally**

:whale: docker volume ls

**Volume command in docker**

:whale: docker run -d --rm -p 3000:80 --name feed-app -v feedback:/app/feedback
 -v "/users/../folderName" -v /app/node_modules feed:volumes

**For container communicating with localhost**

:whale: host.docker.internal

**To get details of container**

:whale: docker container inspect containerName

**Network**

:whale: docker network create networkName

**connecting a container to a network**

:whale: docker run -d --name mongodb --network favorites-network mongo

**starting docker-compose**

:whale: docker-compose up -d

:whale: docker-compose down
