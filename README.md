# quickstart-docker
Quickstart docker.

## Cheat Sheet

### Download image

    $ docker pull [OPTIONS] IMAGE[:TAG]

### Create and start containers

    $ cd ./compose/mongodb
    $ docker compose up --remove-orphans -d

### List containers

**Running containers only**

    $ docker ps

**All containers**

    $ docker ps -a

### Fetch container logs

    $ docker logs [OPTIONS] CONTAINER

### Remove containers

    $ docker rm [OPTIONS] CONTAINER

### Remove images

    $ docker rm [OPTIONS] IMAGE

### Clean up system

    $ docker system prune
