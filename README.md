# Docker workshop

In front of you there is a laptop with Docker toolbox installed.
During the following exercises, you will learn to get along with Docker in the basic way of working, and be able to deploy small containers.
If you have any questions, feel free to ask.

## Basics

First, learn to get started with Docker after our presentation.
We are going to deploy a Busybox container on our docker environment.
Busybox is a small linux environment and a sandbox to play with.

**docker pull busybox**

```sh
$ docker pull busybox
Using default tag: latest
latest: Pulling from library/busybox
```

This way, we will download the image to our docker machine so its ready for use in a container.
Check if the image is correctly downloaded.

***docker images***

```sh
$ docker images
REPOSITORY                TAG                 IMAGE ID            CREATED             VIRTUAL SIZE
busybox                   latest              sha256:47bcc        10 weeks ago        1.113 MB
```
