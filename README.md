# vue-demo-docker
## Build Setup

``` bash
# build docker image
docker build -t vue-demo-docker .

# run docker image at localhost:8081
docker run -it -p 8081:8080 -d vue-demo-docker
```
Best practice would be instead of: (vue-demo-docker) [%yourdockerhandle%/vue-demo-docker].
