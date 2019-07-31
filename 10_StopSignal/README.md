# STOP signals in Dockerfile
> Stop command is used to change the state of a Docker container from Running to blocked.
```Dockerfile
docker stop <docker container ID/Name>
```
> Stop command sends an interrupt signal to change the state.
```
The default signal for stop is SIGTERM.
```
> The stop signal can be overridden using following syntax:
```Dockerfile
STOPSIGNAL <signal>
```
> Example: SIGKILL signal is used to kill docker containers rather than stopping them.
