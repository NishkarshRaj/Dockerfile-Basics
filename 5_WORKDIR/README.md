# WORKDIR command in Dockerfile
```
WORKDIR command is used to set the default workspace.

It overrides the default workspace, i.e, the home directory ~.
All the CMD, RUN commands are executed using this workspace.
```

## Syntax:
```
WORKDIR <absolute path of new workspace>

RUN/CMD ./<path>
```
* Here, . specifies current WORKDIR as current folder.
