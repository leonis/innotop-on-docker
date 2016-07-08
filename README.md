# innotop Dockerfile

This repository contains **Dockerfile** of innotop.

See https://github.com/innotop/innotop about innotop.

## Base Docker image

- [leonisandco/innotop](https://hub.docker.com/r/leonisandco/innotop/)

## Installation

1. Install [Docker](https://www.docker.com/)
2. Download [automated build](https://hub.docker.com/r/leonisandco/innotop/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull leonisandco/innotop`
  (alternatively, you can build an image from Dockerfile: `docker build -t ="leonisandco/innotop" github.com/leonisandco/innotop-on-docker`)

# Usage

## Run innotop

  docker run --rm leonisandco/innotop -h

See [innotop/innotop](https://github.com/innotop/innotop) about how to use innotop.
