This file explains the architecture of Docker.

Docker follows Client-Server architecture.

### 1. Docker Client
Command line tool: ```docker```. 

It is used to run commands like: docker build, docker pull, docker run.

Sends request to Docker Daemon through REST API.

### 2. Docker Daemon (dockerd)
Heart of Docker.

It runs in background.

It builds Images, runs Containers, manages Networks and Volumes.

One can handle multiple clients.

### 3. Docker Registry
It stores and distributes Images.

Default public registry is Docker Hub.
