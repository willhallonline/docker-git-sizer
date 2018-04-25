# Supported tags and respective ```Dockerfile``` links
* ```latest```
* ```alpine```

## What is Git Sizer?



**This is a Dockerised Solution for running Git Sizer**.

## Docker Commands

### Pull

```
docker pull willhallonline/git-sizer:latest
```

### Run on local repo

```
cd ~/your-local-repo
docker run -it --rm -v $(pwd):/app willhallonline/git-sizer
```
