# README

## Quick Start

### build docker image

```shell
docker build -t mydocsify .
```

### run with docker image

```shell
docker run -it -p 3333:3000 --name=docsify -v $(pwd)/docs:/docs mydocsify
```

### test with docker container

```shell
open http://127.0.0.1:3333
```
