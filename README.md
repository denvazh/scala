## Scala

This repository contains experimental **Dockerfile** of [Scala](http://www.scala-lang.org) for [Docker](https://www.docker.com/)'s [automated build](https://registry.hub.docker.com/u/denvazh/scala/) based on [lightweight docker image for OpenJDK7](https://registry.hub.docker.com/u/denvazh/java/).

### Base Docker Image

* [denvazh/java:openjdk7-jdk](https://registry.hub.docker.com/u/denvazh/java/)

### Tags

* `latest` (default): Scala 2.11.6 which is an alias to `2.11.6`
* `2.11.6`: Scala 2.11.6
* `2.11.5`: Scala 2.11.5
* `2.11.4`: Scala 2.11.4
* `2.11.2`: Scala 2.11.2
* `2.11.1`: Scala 2.11.1
* `2.11.0`: Scala 2.11.0
* `2.10.5`: Scala 2.10.5
* `2.10.4`: Scala 2.10.4

Note: Scala version `2.11.3` is NOT included, because it was [released with severe compatibility issues](https://issues.scala-lang.org/browse/SI-8899).

### Installation

1. Install [Docker](https://www.docker.com/)

2. Download [automated build](https://hub.docker.com/u/denvazh/scala) from public registry: `docker pull denvazh/scala`
  
  (alternatively, one can build an image `docker build -t="denvazh/scala" github.com/denvazh/scala`)