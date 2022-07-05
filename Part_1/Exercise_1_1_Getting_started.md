# Exercise 1.1: Getting started

## Commands

```command
docker run -d --name nginx-container nginx
docker run -d --name postgres-container postgres
docker run -d --name redis-container redis

docker stop nginx-container
docker stop postgres-container

docker ps

docker stop redis-container

docker containers purge
docker images purge
```

## Output

```command
C:\Users\diogo>docker ps -a
CONTAINER ID   IMAGE       COMMAND                  CREATED         STATUS                        PORTS      NAMES
7f9e0d2e31f2   redis       "docker-entrypoint.s…"   4 minutes ago   Up 2 seconds                  6379/tcp   redis-container
6dc5aa97c031   postgres    "docker-entrypoint.s…"   5 minutes ago   Exited (1) 5 minutes ago                 postgres-container
d6d5d5ff27ac   nginx       "/docker-entrypoint.…"   5 minutes ago   Exited (0) 2 minutes ago                 nginx-container
```
