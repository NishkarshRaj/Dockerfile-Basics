# HEALTHCHECK command in Dockefiles
```
HEALTHCHECK command is used to keep a regular check on resources used by Docker Container.
A condition is set to identify the health of Docker Container.

If the condition fails during any checkup, a fail condition command is executed.
```

## Syntax:
```Dockerfile
HEALTHCHECK --interval=<Numbers in ms> --timeout=<Numbers in ms> --retries=<number of retries> <command to check health of container> || <Command to be executed on failure>
```
> Interval: Time gap between checkups. <Number>s like 5s gives input in seconds
> Timeout: Time gap given for condition of healthcheckup to execute successfully.
> Retries: Number of times a failure is ignored.
