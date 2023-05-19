# python

Dockerized python and libs.

## Software

- alpine 3.8
- python3.6
- python libs: beautifulsoup4,lxml,requests

## Docker

[![Generic badge](https://img.shields.io/badge/hub.docker.com-vfabi/python-<>.svg)](https://hub.docker.com/repository/docker/vfabi/python)  
[![Generic badge](https://img.shields.io/badge/quay.io-vfabi/python-<>.svg)](https://quay.io/vfabi/python)

## Build

```sh
docker buildx build --push --platform=linux/amd64,linux/arm64 -t vfabi/python:XXX -f Dockerfile .
docker buildx build --push --platform=linux/amd64,linux/arm64 -t quay.io/vfabi/python:XXX -f Dockerfile .
```

## Contributing

Please refer to each project's style and contribution guidelines for submitting patches and additions. In general, we follow the "fork-and-pull" Git workflow.

 1. **Fork** the repo on GitHub
 2. **Clone** the project to your own machine
 3. **Commit** changes to your own branch
 4. **Push** your work back up to your fork
 5. Submit a **Pull request** so that we can review your changes

NOTE: Be sure to merge the latest from "upstream" before making a pull request!

## License

Apache 2.0
