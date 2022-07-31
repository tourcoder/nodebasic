NodeBasic
======

The node docker file with basic functionality


### How to use nodebasic

Use as base image in Dockerfile

- From Docker Hub

  ```
  FROM tourcodercom/nodebasic
  ```

- From GitHub 

  ```
  FROM docker.pkg.github.com/tourcoder/nodebasic/nodebasic:latest
  ```

Download `Dockerfile` in this repo, and run

```
docker build -t nodebasic .
```

### License

[MIT License](LICENSE)
