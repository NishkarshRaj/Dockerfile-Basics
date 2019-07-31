# ENTRYPOINT command in Dockerfile
```
ENTRYPOINT command is similar to the CMD command.

It is used to execute a set of commands when the Docker Container is created.
```

# CMD versus ENTRYPOINT
> Before the difference, note the following for *Docker run* command:
```
docker run -it --rm <Docker Image name> <set of commands>

Example: docker run -it --rm ubuntu ls
```

> Thus, we can give CMD commands to be run when the container launches explicitly when container is created using docker run command.
> This is important when we want to run some commands for current container but not for all images.

### Difference:
```
When we add explicit commands during creation of Docker container,

* CMD commands are overridden and only explicit commands are executed not the CMD commands of Docker Image.
* ENTRYPOINT commands are not overridden and they are static.
```

## Challenge :smile:
```
Try Using both CMD and ENTRYPOINT commands in same Dockerfile in different order in same Dockerfile. 
```
