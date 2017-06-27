# docs-docker

Docker image for build document to html files.

## build local image

```sh
$ docker build -t ci-docs .
```

## How to use

Run with online image

```sh
$ docker run --rm -ti -v $(PWD):/home/ci appleboy/codeigniter-docs /bin/bash
```
