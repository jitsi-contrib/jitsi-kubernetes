# Jitsi on Kubernetes

[Jitsi](https://jitsi.org/) is a set of Open Source projects that allows you to easily build and deploy secure videoconferencing solutions.

This repository provides tools and tutorials to run the [Jitsi Meet](https://jitsi.org/jitsi-meet/) stack in a [Kubernetes Cluster](https://kubernetes.io/). The stack is based on the official docker images provided by the [Docker Jitsi-meet project](https://github.com/jitsi/docker-jitsi-meet).


<p align="center"><img src="./resources/jitsi-docker-kubernetes.png" width="400"/></p>


There are quite a few different ways to deploy Jitsi with Kubernetes, not to mention different parameters as well depending on how you want it to scale. The following section provides examples, tutorials and general information how to run jitsi in a Kubernetes Cluster.  


 - [Kubernetes Kustomize](doc/kustomize/README.md) - a simple deployment based on Kubernetes kustomize  allowing you to configure your jitsi setup in an easy and transparent way. 
 - [Migration from Docker-Compose](doc/kompose/README.md) - if you already have a docker-compose stack running jitsi this will help you to migrate to Kubernetes.
 - [Helm](https://github.com/jitsi-contrib/jitsi-helm)
 - [Secure jitsi on Kubernetes](#) - TBD


# How to Contribute

You are sincerely invited to participate in it. If you want to share your thoughts or contribute to this project please report any issues here. All source are available on Github.
