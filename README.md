# Pino in Docker

A small Docker layer containing [Pino](http://getpino.io/). It is intended as a quick way to use the `pino` command on arbitrary Docker hosts without installing Node, NPM and Pino.

## Usage

```bash
docker logs --tail=100 -f CONTAINER_ID | docker run -i --rm eoinsha/pino
```
