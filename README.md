Docker-Java8
============

## Summary

Repository name in Docker Hub: **[re6exp/debian-jessie-oracle-jdk-8](https://registry.hub.docker.com/u/re6exp/debian-jessie-oracle-jdk-8/)**

This repository contains Dockerized [Java](https://www.java.com/) 1.8, published to the public [Docker Hub](https://registry.hub.docker.com/) via **automated build** mechanism.



## Configuration

This docker image contains the following software stack:

- OS: Debian jessie (built from [re6exp/debian-jessie](https://github.com/re6exp/debian-jessie)).

- Java: Oracle JDK 1.8.0_X


### Dependencies

- [re6exp:debian-jessie](https://registry.hub.docker.com/u/re6exp/debian-jessie/).



## Alternatives

- [williamyeh/java8](https://registry.hub.docker.com/u/williamyeh/java8/) - this image based on William's work.

- [errordeveloper/oracle-jdk](https://registry.hub.docker.com/u/errordeveloper/oracle-jdk/), if you prefer a minimalistic Oracle JDK 8 container on top of busybox.

- [java](https://registry.hub.docker.com/_/java/) or [azul/zulu-openjdk](https://registry.hub.docker.com/u/azul/zulu-openjdk/), if you prefer OpenJDK.

## Installation

   ```
   $ docker pull re6exp/debian-jessie-oracle-jdk-8:latest
   ```


## Usage

Can be used as a base image for other Java-based development environment.


#### Run `java`

```
$ docker run --rm re6exp/debian-jessie-oracle-jdk-8
```


#### Run `javac`

```
$ docker run -it --rm re6exp/debian-jessie-oracle-jdk-8 javac
```


### Dig into container

```
$ docker run -it re6exp/debian-jessie-oracle-jdk-8 /bin/bash
```

