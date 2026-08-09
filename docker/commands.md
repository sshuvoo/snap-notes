To create a image

```bash
docker build -t <image_name> .
```

To Run a image

```bash
docker run -it --name <container_name> <image_name> bash
```

To enter into a running container

```bash
  docker exec -it <container_name> bash
```

# To shows all the images

```bash
  docker images -a
```

# To shows all the running containers

```bash
  docker ps
```

# To shows all the containers

```bash
  docker ps -a
```

# To stop a running container

```bash
  docker stop <container_name>
```

# To remove a stopped container

```bash
  docker rm <container_name>
```

# To remove all the stopped containers

```bash
  docker container prune
```

# To start a stopped container

```bash
  docker start <container_name>
```

# To restart a container

```bash
  docker restart <container_name>
```
