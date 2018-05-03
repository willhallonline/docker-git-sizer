# Docker Git Sizer

## Supported tags and respective ```Dockerfile``` links
* ```latest```, ```alpine``` [alpine/Dockerfile](https://github.com/willhallonline/docker-git-sizer/blob/master/alpine/Dockerfile)
* ```slim```, [slim/Dockerfile](https://github.com/willhallonline/docker-git-sizer/blob/master/slim/Dockerfile)

## What is Git Sizer?

[Git Sizer](https://github.com/github/git-sizer) is a tool to Compute various size metrics for a Git repository, flagging those that might cause problems.

**This is a Dockerised Solution for running Git Sizer**.

## Docker Commands

### Pull

```
docker pull willhallonline/git-sizer:alpine
```

### Run on local repo

```
cd ~/your-local-repo
docker run -it --rm -v $(pwd):/app willhallonline/git-sizer:alpine
```
