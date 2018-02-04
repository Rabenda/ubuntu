## Ubuntu Dockerfile


This repository contains **Dockerfile** of [Ubuntu](http://www.ubuntu.com/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/library/ubuntu/)

## Murphi3.1-fix
[automated build](https://github.com/Rabenda/Murphi3.1-fix)


### Base Docker Image

* [ubuntu:16.04](https://hub.docker.com/r/library/ubuntu/)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/rabenda/ubuntuwithmurphi3.1/) from public [Docker Hub Registry](https://hub.docker.com/): `docker pull rabenda/ubuntuwithmurphi3.1`

   (alternatively, you can build an image from Dockerfile: `docker build -t="rabenda/ubuntuwithmurphi3.1" github.com/rabenda/ubuntuwithmurphi3.1`)


### Usage

    docker run -it --rm rabenda/ubuntuwithmurphi3.1
