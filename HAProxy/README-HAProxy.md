# HAProxy on Docker

## Introduction

In this section, I'll demonstrate how to configure a HAProxy server that fronts some web servers. The HAProxy will be hosted on a Docker container with a TCP port exposed on the Docker host. This is the port clients will use to access the web servers behind.

To test the load balancing capability of HAProxy, I've built a Docker container with Nginx and PHP8. The default web page

![Architecture](../images/architecture.png)  

## Requirements:

* Familiarity with [Docker](https://www.docker.com/).
* Docker Desktop installed locally.
