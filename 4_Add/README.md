# ADD command in Dockerfile
```
ADD command is similar to the COPY command in the following way:
They are both used to create a copy of the specified local directory in the container.

The difference is that ADD command has more features.
If the specified file/directory is:

* A compressed file like tar,rar etc. : It is decompressed.
* A downloadable file: It is downloaded etc.
```

## Syntax:
```
ADD <absolute path of the local file/directory> <destination in container>
```
