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

- running container

```
docker run -d --name express-container -p 3333:3333 express-app
```

- to check running container

```
docker ps
```

- to remove totally

```
docker remove express-app
```

- to stop the container

```
docker stop express-container   #do clean away and they stop the container
docker kill express-container   # do right away
```
