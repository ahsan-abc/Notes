
## what

- Docker is a container platform that allows you to build, test and deploy applications quickly
- A developer defines all the applications and it’s dependencies in a Dockerfile which is then used to build Docker images that defines a Docker container.
- Doing this ensures that your application will run in any environment

## why

- Microservices, Data Processing, Continuous Integration and Delivery, Containers as a Service.  
    ![[docker2.png]]   
    ![[docker5.png]]
    ![[docker3.png]]

## Docker Image

- A Docker Image is a file that defines a Docker Container.
- image (class) , containers (instance)

## Docker container

- A container is a runnable instance of an image.

## Build docker image

1.  Create a file named ‘Dockerfile’
2.  inside put
    - FROM ubuntu  
        MAINTAINER kunal kushwaha [kunal@gmail.com](mailto:kunal@gmail.com)  
        RUN apt-get update  
        CMD \[“echo”, “Hello World”\]
3.  cmd : `docker build -t "tag_name" .`

## Docker architecture

![[docker4.png]]

## Docker components

![[docker1.png]]

## Docker daemon

## Docker client

## Docker registries

## Docker Daily use commands

1.  **docker –version**  
    This command is used to get the currently installed version of docker
    
2.  **docker pull**  
    Usage: docker pull &lt;image name&gt;  
    This command is used to pull images from the docker repository(hub.docker.com)
    
3.  **docker run**  
    Usage: docker run -it -d &lt;image name&gt;  
    This command is used to create a container from an image
    
4.  **docker ps**  
    This command is used to list the running containers
    
5.  **docker ps -a**  
    This command is used to show all the running and exited containers
    
6.  **docker exec**  
    Usage: docker exec -it &lt;container id&gt; bash  
    This command is used to access the running container
    
7.  **docker stop**  
    Usage: docker stop &lt;container id&gt;  
    This command stops a running container
    
8.  **docker kill**  
    Usage: docker kill &lt;container id&gt;  
    This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it
    
9.  **docker commit**  
    Usage: docker commit &lt;conatainer id&gt; &lt;username/imagename&gt;  
    This command creates a new image of an edited container on the local system
    
10. **docker login**  
    This command is used to login to the docker hub repository
    
11. **docker push**  
    Usage: docker push &lt;username/image name&gt;  
    This command is used to push an image to the docker hub repository
    
12. **docker images**  
    This command lists all the locally stored docker images
    
13. **docker rm**  
    Usage: docker rm &lt;container id&gt;  
    This command is used to delete a stopped container
    
14. **docker rmi**  
    Usage: docker rmi &lt;image-id&gt;  
    This command is used to delete an image from local storage
    
15. **docker build**  
    Usage: docker build &lt;path to docker file&gt;  
    This command is used to build an image from a specified docker file


[link with debops](DEVOPS.md)