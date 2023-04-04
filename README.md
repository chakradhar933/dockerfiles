### Dockerfiles

Dockerfile is declaritive way of creating our own images. Docker will give some syntax to create our own images.
File name should be Dockerfile .

### How to build image from the Dockerfile

```
docker build -t [dockerhub url]/[dockerhub-username]/[image-name]:version .
```
# "." denote the current directory.

### how to push image to docker to dockerhub

```
docker push [dockerhub-url]/[dockerhub-username]/[image-name]:version
```
