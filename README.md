# About

Dockerfile to build a pgplot image based on CentOS.

# How to run

Just type the following commands

```
# On Linux
$ docker run -it -e DISPLAY=unix$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix shaoguangleo/centos-pgplot

# On MacOSX
# IP=$(ifconfig en1 | grep inet | awk '$1=="inet" {print $2}')
$ docker run -it -e DISPLAY=$IP:0 shaoguangleo/centos-pgplot
```

As we all know, the version can be `lateset` or `$ cat VERSION`

# TODO

recompile using -fPIC flag

# travis

[![Build Status](https://www.travis-ci.org/shaoguangleo/docker-centos-pgplot.svg?branch=master)](https://www.travis-ci.org/shaoguangleo/docker-centos-pgplot)
