# About

Dockerfile to build a pgplot image based on CentOS.

# How to run

Just type the following commands

```
# On Linux
$ docker run -it -e DISPLAY=unix$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix shaoguangleo/centos-pgplot

# On MacOSX (ARM also support)
$ xhost + 127.0.0.1 
$ docker run -it -e DISPLAY=docker.for.mac.host.internal:0 -v /tmp/.X11-unix:/tmp/.X11-unix shaoguangleo/centos-pgplot:latest
```

As we all know, the version can be `lateset` or `$ cat VERSION`

# TODO

recompile using -fPIC flag

# travis

[![Build Status](https://www.travis-ci.org/shaoguangleo/AstroSoft.svg?branch=master)](https://www.travis-ci.org/shaoguangleo/AstroSoft)
