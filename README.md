# centos-7-docker

## Build Container
```
$ sudo docker image build -t centos-7-image:0.0 .
```
## Run Container
```
$ sudo docker container run -itd --name my-centos-7 centos-7-image:0.0
```
## Access Container
$ sudo docker exec -it centos-7 /bin/bash


