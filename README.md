# Rdns-server tests

## Build image
`docker build -t wchao241/dind .`

## Run the dind-container
`docker run --privileged -d --publish=2222:22 image_id`

## ssh dind-container
```
ssh -p 2222 root@IP
```

## Execute docker command
`docker version`

```
Client:
 Version:      18.05.0-ce
 API version:  1.37
 Go version:   go1.9.2
 Git commit:   f150324
 Built:        Wed May  9 22:11:29 2018
 OS/Arch:      linux/amd64
 Experimental: false
 Orchestrator: swarm

Server:
 Engine:
  Version:      18.05.0-ce
  API version:  1.37 (minimum version 1.12)
  Go version:   go1.10.1
  Git commit:   f150324
  Built:        Wed May  9 22:20:42 2018
  OS/Arch:      linux/amd64
  Experimental: false
```
