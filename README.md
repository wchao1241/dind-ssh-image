# Rdns-server tests

## Build image
```
docker build -t wchao241/dind .
```

## Run the dind-container
```
docker run --privileged -d --publish=2222:22 image_id
```

## ssh dind-container
```
ssh -p 2222 root@IP
```
