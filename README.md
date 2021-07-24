# Record and Stream to Multiple Services

![🏖️ Sandbox (WIP)](https://img.shields.io/badge/status-wip-red)

CommPlex is a simple communications utility for live streaming to
multiple services concurrently and periodically saving and publishing
recorded videos (with full descriptions) from the stream while doing it.

## Install

1. Install OBS Studio
1. Install Docker (or Docker Desktop)
1. Download and validate the `cmx` executable

## Usage

```
cmx config (<name> [<value>])
cmx startup 
cmx shutdown
cmx record
cmx stop
```

## FAQ

### Why not just use clips?

Clips are usually limited in duration and don't allow additional
description information. Usually clips are just metadata pointing to a
start and end within a larger video. Locally recorded video segments of
any length can also be tied to other written communication systems (such
as a personal Zettelcasten repo).
