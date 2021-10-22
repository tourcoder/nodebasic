NodeBasic
======

The node docker file with basic functionality


### How to use nodebasic

Use as base image in DockerFile

```
FROM docker.pkg.github.com/tourcoder/nodebasic/nodebasic:latest
```

Or pull image from the command line

```
docker pull docker.pkg.github.com/tourcoder/nodebasic/nodebasic:latest
```

### How to build nodebasic docker

Download `Dockerfile` in this repo, and run

```
docker build -t nodebasic .
```

### License

MIT
