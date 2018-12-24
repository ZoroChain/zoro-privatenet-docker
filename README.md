# zoro-cli-docker
Docker on windows with Centos Linux OS.

## Prepare docker environment

https://docs.docker.com/docker-for-windows/install/
Install docker on windows.

## Clone & Build images

Build docker images
docker build -t zoro-cli:v0.3 C:\_zoro\zoro-privatenet-docker\Dockerfile\privatenet

## Start docker nodes
cd C:\home\zoro-cli-docker\Dockerfile\privatenet
docker-compose up

## Run Shell in container
docker exec -it cli1 /bin/bash

## Cli RPC
http://127.0.0.1:10332
