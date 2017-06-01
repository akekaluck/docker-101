# docker-101

# Dockerfile
## Shell form
- CMD /bin/cd /user/
- RUN cd /usr

## Exec form
- CMD ["executable","param1", "param2"]
- RUN ["cd","/user"]

## CMD vs ENDPOINT vs RUN
- RUN = Run when create a image
### Default executeable (Execute when no command)
- CMD = If run docker command with options, it will be ignored.
- ENDPOINT = Always run.

# WORKDIR: 

# docker-compose
## docker-compose -f [File name] up 
- docker-compose.yml (Default
- docker-compose.override.yml

# docker with artifactory
- docker login [artifact url]
- docker logout [artifact url]

# docker-compose
- extra_hosts: set host file in container


