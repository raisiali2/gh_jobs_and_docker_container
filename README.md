# jobs & docker containers

## module introduction

## what are containers?
the idea behind container is to run our code independent of the machine configuration and settings.
- packages that container code + its execution environment
- advantage: reproducible execution environment & results


## why might you want to use containers (with github actions)?
- you can define container by set up docker file using `From` the base image you want to create you container
- define env vars you want to use in the container
- working directory
- package and dependencies need to install for the container using `RUN` and `COPY` 

## demo project setup & a dockerfile

## run jobs in container

## service containers - theory

## adding services (via service containers)

## communication between jobs & service containers

## module summary