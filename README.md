# Docker-Commands

# Command uses

### Create image

```
docker build -t <Image-Name> .
```

### Create image for specific platform like linux/amd64

```
docker  build --platform <platform-name >   -t <Image-Name>  .

```

```
docker buildx build --platform linux/amd64 -t <Image-Name> .

```

### Create Image and also push to docker hub

```
docker  build --platform linux/amd64 -t <username/image-name> --push .
```

### Move into any container

```
docker exec -it <conatiner_id-or-name > /bin/bash

```
