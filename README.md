# Docker
Docker Containers and Images using Go and DockerFile.

## Content:

1. Dockerfiles
  * [FROM and RUN command](https://github.com/NishkarshRaj/Dockererfile-Basics/tree/master/1_from_run_keyword)
  * [CMD command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/2_CMD)
  * [COPY command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/3_Copy)
  * [ADD command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/4_Add)
  * [WORKDIR command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/5_WORKDIR)
  * [ENTRYPOINT command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/6_Entrypoint)
  * [ENV command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/7_Env)
  * [LABEL command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/8_Label)
  * [HEALTHCHECK command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/9_HealthCheck)
  * [STOPSIGNAL command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/10_StopSignal)
2. Persistent Storage
  * [Volume](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/Persistent%20Storage/Volume)
  * [Mount](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/Persistent%20Storage/Mount)
3. Networking
  * [EXPOSE command](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/Networking/1-EXPOSE)
  * [Subnetting Network](https://github.com/NishkarshRaj/Dockerfile-Basics/tree/master/Networking/Network)


# Basics of Dockerfile
  
## Creation of Dockerfile

**Syntax:**
```
vi Dockerfile
```
   
## Building a Dockerfile to create Docker Image
**Syntax:**
```docker
docker build -t <docker image name> <path of Dockerfile>
```
*Generally, Dockerfiles are stored on current path of build and must be specified by wildcard character .*

## Running a Docker Image to create Docker Container
**Syntax:**
```docker
docker run -it --name <Docker Container Name> --rm <Docker image name> <list of executable commands separated by ;>
```
