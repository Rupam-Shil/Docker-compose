- write the dockerfile
- create .dockerignore
- to create the image run this command

```
docker build -t express-app:v2 .
# the -t flag is to name the image
```

```
docker images
# to see the images
```

```
docker image rm express-app:v2
# to remove the image
```
