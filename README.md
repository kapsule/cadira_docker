# Docker Cadira / Vtiger Open Source

This project uses the resources defined in the (https://github.com/javanile/vtiger) repository to adapt the Cadira Open Source project (fork of VTiger Open Source).

## Installation in Linux Ubuntu / Debian:

- Installation of the required packages

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin

- Enable permissions to run docker

sudo chmod 666 /var/run/docker.sock

## Compile docker file to create a VTiger instance in Docker:

- Create dir vtiger
- git clone [repository] vtiger
- cd vtiger
- docker build -t vtiger:v1 .
