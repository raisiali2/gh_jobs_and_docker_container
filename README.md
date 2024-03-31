# jobs & docker containers

## module introduction

## what are containers?
the idea behind container is to run our code independent of the machine configuration and settings.
- packages that container code + its execution environment
- advantage: reproducible execution environment & results


## why might you want to use containers (with github actions)?
there are two possibilities either we run our github action on the the runner or inside container on the runner, if we run directly on the host machine we are limited to the host machine setup, and when run on the container we are free to setup our own environment and then implement this container on the runner but in this case all the steps we be ran inside the container.

- you can define container by set up docker file using `From` the base image you want to create you container
- define env vars you want to use in the container
- working directory
- package and dependencies need to install for the container using `RUN` and `COPY` 
  
![why use container](image.png)

![container & github actions](image-1.png)

- with container you have full control over environment & installed software
- just the runner: choose from list of predefined environment(include installed software)

## demo project setup & a dockerfile

## run jobs in container

## service containers - theory

## adding services (via service containers)

## communication between jobs & service containers

## module summary