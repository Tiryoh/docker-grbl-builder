# docker_grbl-builder

[![Build Status](https://travis-ci.com/Tiryoh/docker_grbl-builder.svg?branch=master)](https://travis-ci.com/Tiryoh/docker_grbl-builder)

![](https://img.shields.io/docker/automated/tiryoh/grbl-builder.svg)
![](https://img.shields.io/docker/build/tiryoh/grbl-builder.svg)
![](https://img.shields.io/docker/pulls/tiryoh/grbl-builder.svg)

Docker container to build grbl

## Usage

run the following command in your grbl directory:

```
docker run --rm -it -v "${PWD}":/source tiryoh/grbl-builder:latest make
```

## Docker Hub

https://hub.docker.com/r/tiryoh/grbl-builder/

## License

The [MIT License](./LICENSE)
