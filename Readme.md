# Readme for ergw-host

The purpose of this repository is to provide host images for running errGW-contianers on.

In the current architecture, erGW needs a custom kernel module to function.
To make it easier for you, to try out your architecture, we provide ready made
images to execute the containers including the kernel modules.


## Usage

To try out erGW components, clone this repository and copy the needed repositories into it.
Afterwards run:

```shell
cd ergw-host
vagrant up
vagrat ssh host
host> cd /vagrant
#execute your commands, for example
host> cd docker
docker-compose up
```
