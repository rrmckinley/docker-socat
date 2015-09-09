# docker-socat


## Quickstart

Build the image:
```bash
docker build -t socat .
```



Run docker-socat and get a shell where you can play, and docker daemon logs
to stdout:
```bash
docker run --privileged -t -i -v /var/run/docker.sock:/var/run/docker.sock -p 4243:4243 socat
```
