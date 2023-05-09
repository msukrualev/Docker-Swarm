# Docker-Swarm-Projects Intro

# What is Docker Swarm?

## Orchestration
- The `portability and reproducibility` of a containerized process means we have an opportunity to `move and scale` our containerized applications across clouds and data centers. 
- Furthermore, as we scale our applications up, we’ll want some tooling to help automate the maintenance of those applications, able to replace failed containers automatically and manage the rollout of updates and reconfigurations of those containers during their lifecycle.
- Containers are great, but when you get lots of them running, at some point, you need them all working together in harmony to solve business problems.


- Docker Swarm is a container orchestration tool built and managed by Docker, Inc. 
- It is the native clustering tool for Docker. 
- Swarm uses the standard Docker API, i.e., containers can be launched using normal docker run commands and Swarm will take care of selecting an appropriate host to run the container on. 
- The tools that use the Docker API can use Swarm without any changes and take advantage of running on a cluster rather than a single host.


# But why do we need Container orchestration System?

Imagine that you had to run hundreds of containers. You can easily see that if they are running in a distributed mode, there are multiple features that you will need from a management angle to make sure that the cluster is up and running, is healthy and
more.

Some of these necessary features include:

● Health Checks on the Containers <br>
● Launching a fixed set of Containers for a particular Docker image<br>
● Scaling the number of Containers up and down depending on the load<br>
● Performing rolling update of software across containers<br>
● and more…<br>

Docker Swarm has capabilities to help us implement all those great features - all through simple CLIs.
