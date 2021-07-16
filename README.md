## Building Image

```
docker build -t node-express:1.0.0 .
```

## Check Images

```
docker images
```

## Run the container based on the image

```
docker run -p 3000:3000 node-express:1.0.0
```

## Check the current containers

```
docker container ls -a
```

## Remove the container

```
docker rm <container_ID>
```
