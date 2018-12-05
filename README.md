# docker_grbl-builder
Docker container to build grbl

## Usage

run the following command in your grbl directory:

```
docker run --rm -it -v "${PWD}":/source tiryoh/grbl-builder:latest make
```

## License

The [MIT License](./LICENSE)
