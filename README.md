# dockerfiles

Dockerfiles for creating customized images 

## Getting started

If you want to customize these images or build them yourself (instead of using mine from dock hub) run:

```shell
# To build the almalinux "ssh`ble" image
docker build -f Dockerfile.almalinux -t almalinux-ssh .

docker build -f Dockerfile.ubuntu-server -t ubuntu-server-ssh .

```
