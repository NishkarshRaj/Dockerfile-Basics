# CMD command

```
CMD commands consists of a list of statements separated by ;
Each statement is executed line by line in an interpreted fashion.
These statements consists of Linux shell commands.

These commands are executed and corresponding result is shown when the Docker container is launched.
```

# CMD verus RUN commands

```
Both CMD and RUN commands consists of set of statements having Linux commands.
The basics difference is that:

RUN commands are executed during creation of Docker Image.
CMD commands are executed during creation of Docker Container.
```

# Important Note related CMD and creation of container.

**Syntax of creation of container:**

```docker
docker run -it --rm <docker image name>
```
```
Here,
-it is used to open the container in interactive mode

If, -it is not used:
Docker Container launches itself, executes the CMD commands, shows its output and the container gets destroyed.
```
