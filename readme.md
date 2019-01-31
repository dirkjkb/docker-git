# Docker Helm
This is a minimal Helm Docker image.
The idea of this container is to have git while building a container.
The new container contains the following:
 - docker
 - bash
 - git

### Docker Build
```
docker build -t dirkjkb/docker-git .
```
### Docker Run
```
docker run dirkjkb/docker-git
```