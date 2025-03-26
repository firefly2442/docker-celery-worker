# docker-celery-worker

## Introduction

A basic Celery worker in a Docker container.

## Requirements

* Docker (with buildkit enabled, see `/etc/docker/daemon.json`)

## Installation and Setup

```shell
docker build -t ghcr.io/firefly2442/docker-celery-worker:latest .
# OR
docker pull ghcr.io/firefly2442/docker-celery-worker:latest
```

## References

* [Celery Homepage](https://docs.celeryq.dev/en/stable/#)
