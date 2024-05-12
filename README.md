# docker-course-youtube

Video in question: https://www.youtube.com/watch?v=3c-iBn73dDE

## What is Docker?

### What is a container
A way to package application with all the necessary dependencies and configurations: portable, easily shared and moved around.
Thus, makes development and deployment very easy.

### Where do containers live?
In a container repository (public/private)

### How do containers improve the development process?
- Before containers: every developer installs dependencies on local environment (different on each OS) (= dependency version conflicts); Many different steps where something could go wrong.
- After containers: dependencies are not installed directly on OS, because container is its own isolated environment packaged with needed configuration (no configuration needed); One step to fetch and start the container.

### How can containers improve the deployment process?
- Before containers: developers produces artifacts with instructions to install the artifact on the server and hands them over to operations (to deploy application); Dependency version conflicts + misunderstanding between development and operations.
- After containers: developers and operations work together to package the application in a container; One step to pull and run container image.

## What is a Container?

## Docker vs Vitual Machine
## Docker Installation
## Main Docker Commands
## Debugging a container
## 

Video in question: https://www.youtube.com/watch?v=pTFZFxd4hOI

## What is docker?
A platform for consistently building, running and shipping applications (each application with its dependencies run inside an isolated environment: application can easily run on multiple machines; application can easily be set up and removed)

## Virtual machines vs containers
A container is isolated environment for running an application. A virtual machine is an abstraction of a machine (f.e. running windows on mac). Hypervisors (f.e. VirtualBox) are used to manage vitual machines. So, run application in isolation in a virtual machine. On the same physical machine, different virtual machine running different applications with different dependencies. But a lot of problems with virtual machine: mainly, separate OS, resource intensive. 

Containers are more lightweight: no separate OS, less hardware resources.

## Architecture of Docker
Docker uses a client-server architecture. The client component talks to the server component using a REST API. The server takes care of building and running docker containers. Containers share the kernel of the OS. Kernel manages applications and hardware resources. Every OS has its own kernel with each kernel its own API. 

## Installing Docker
## Development workflow


