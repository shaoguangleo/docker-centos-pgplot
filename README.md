# About

Dockerfile to build a pgplot image based on CentOS.

# How to run

Just type the following commands

```
$ docker run -it -e DISPLAY=unix$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix shaoguangleo/centos-pgplot
```

As we all know, the version can be `lateset` or `$ cat VERSION`

# travis

[![Build Status](https://www.travis-ci.org/shaoguangleo/docker-centos-pgplot.svg?branch=master)](https://www.travis-ci.org/shaoguangleo/docker-centos-pgplot)
