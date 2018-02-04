## Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](registry.cn-hangzhou.aliyuncs.com/personal_rabenda/ubuntu)


### Base Docker Image

* [ubuntu:16.04](https://registry.hub.docker.com/u/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](registry.cn-hangzhou.aliyuncs.com/personal_rabenda/ubuntu)

   `docker pull dockerfile/ubuntu`

   (alternatively, you can build an image from Dockerfile: `docker build -t="Rabenda/ubuntu" github.com/Rabenda/ubuntu`)


### Usage

    docker run -it --rm personal_rabenda/ubuntu
