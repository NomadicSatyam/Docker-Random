# Docker-Commands

# Command uses

### Create image

```bash
docker build -t <Image-Name> .
```

### Create image for specific platform like linux/amd64

```bash
docker  build --platform <platform-name >   -t <Image-Name>  .

```

```bash
docker buildx build --platform linux/amd64 -t <Image-Name> .

```

### Create Image and also push to docker hub

```bash
docker  build --platform linux/amd64 -t <username/image-name> --push .
```

### Move into any container

```bash
docker exec -it <conatiner_id-or-name > /bin/bash

```

### Command to execute docker-compose file in detach mode

```bash
docker-compose up -d
```

```bash
docker-compose down -v
```
