# docker-ndnSIM
A container

```
docker build -t ndnsim .

docker run -t -i -h ndn -e DISPLAY=$DISPLAY -v /tmp/.X11-unix/:/tmp/.X11-unix/ndnsim:latest
```
