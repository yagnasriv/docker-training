## Containerization Tool ##
# Docker
_____________________________

- Docker is a Containerization platform that provides easy ways to containerize an application, which means using Docker you can build container images, run the images to create a CONTAINERs and also push these containers to container registries such as Docker registry. 

### Docker architecutre 
Docker deamon is brain of Docker. 
Dockerfile - Dockefile is a file where you provide steps for building a docker image.

### Commands used to create a Docker image 
- docker build -> Builds docker image from Dockerfile
    <Syntax: docker build -t docker-username/registry-name:tagname .>
- docker run -> Runs container from docker image
    <Syntax: docker run docker-username/registry-name:tagname>
- docker push -> pushes the container image to public/private registires to share the docker images.
    <Syntax: docker push docker-username/registry-name:tagname>
- docker images -> lists the docker images from the host machine
- docker ps -> lists the running containers on the hostmachine
- docker stop -> stops a running container
- docker start -> starts a stopped container
- docker rm -> removes a stopped continer 
- docker rmi -> removes an image from the host machine
- docker network -> manages docker netowrk such as creating and removing netowrks and connecting containers to network

_________________________________________________________________________________

## Containerising a Web Application / Django Application 
- Install Docker on a EC2 instace 
- Run a simple application on Docker
- build the image 
- push the image to docker registry for making it available to public
_____________________________________________________________________________

### Containerising a Django Application
- As a devops engineer need to know how to containerize a Django Application
- Workflow of Django Application
    - (should have knowledge of how to run a java, python, node js application)
    - refer djnago documentation
    - start with installing django, install python and install django using pip command,
    - or download it through internet
    - ex: import django
    - NOTE: django admin using pip install django, pip install django admin command for installation
    - django admin is similar to ansible galaxy
    - what ansible galaxy does ? give a sekelton of a ansible role
- create a project name ' Devops'
- Syntax: django admin start project 'DEvops'
- created a project, 
