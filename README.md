# vue-demo-docker
## Build Setup

``` bash
# build docker image
docker build -f '%Dockerfile path%' -t %yourdockerhandle%/vue-demo-docker .

# run docker image at localhost:8081
docker run -it -p 8081:8080 -d %yourdockerhandle%/vue-demo-docker
```
