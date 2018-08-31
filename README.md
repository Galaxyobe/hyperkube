# hyperkube

github addr [https://github.com/kubernets/hyperkube](https://github.com/kubernets/hyperkube)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/hyperkube/raw/master/get-hyperkube-image.sh

## Arch and Version

- [**amd64** v1.10.7](https://hub.docker.com/r/kubernets/hyperkube-amd64)

    > docker pull kubernets/hyperkube-amd64:v1.10.7

    > docker tag kubernets/hyperkube-amd64:v1.10.7 gcr.io/google_containers/hyperkube-amd64:v1.10.7 

    > docker rmi kubernets/hyperkube-amd64:v1.10.7
