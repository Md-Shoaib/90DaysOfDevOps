# Day 12: Docker for DevOps Engineers.

## What is Docker and how does it work?
Docker is an open-source platform that allows developers to easily create, deploy, and run applications in containers. Containers are a form of lightweight virtualization that allows developers to package an application and its dependencies together in a single, portable container.

Docker uses a technology called containerization to create and manage containers. In a containerized application, each component of the application runs in its own container. This allows for greater consistency and predictability in the application's runtime environment, as well as the ability to easily move the application between different environments.

Docker uses a client-server architecture. The Docker daemon (also known as the Docker engine) runs on the host machine and is responsible for managing the containers. The Docker client is a command-line tool that communicates with the Docker daemon to create, start, and stop containers, as well as perform other tasks.

Docker images are the blueprint for a container. An image is a pre-configured file system, with all the necessary software and dependencies to run the container. Once an image is created, it can be used to create any number of containers. All containers created from the same image will have the same software and dependencies, which ensures that the application runs consistently across different environments.

Docker provides a central repository called Docker Hub, which allows users to share and discover images. Users can also create their own local images, which can be used to distribute and share applications within their own organization.

## What are Docker images and how are they used?
Docker images are the building blocks of containerized applications in Docker. They are essentially snapshots of an application's file system, including all the necessary files, libraries, and dependencies to run the application.

An image is created by defining a set of instructions in a special file called a Dockerfile. The Dockerfile specifies things like the base image to use, the software to install, and any configuration changes to make. When the Dockerfile is processed, it generates a new image.

## What is a Docker container and how is it different from a virtual machine?
A Docker container is a running instance of a Docker image. It is a lightweight, standalone, and executable package that contains everything needed to run a piece of software, including the code, a runtime, system tools, libraries, and settings.

Docker containers are different from virtual machines (VMs) in several ways:

- VMs emulate hardware and run an entire operating system, while containers share the host's kernel and run on top of the host's operating system.

- VMs are typically heavier and slower to start than containers, as they require more system resources to emulate the hardware.

- Containers use less system resources than VMs, which makes them more efficient and scalable.

Docker provides several commands to manage containers, such as `docker run` to start a new container, `docker stop` to stop a running container, and `docker ps` to list all running containers.

# Tasks to solve
- Use the `docker pull` command to download an image from a public repository such as Docker Hub.
- Use the `docker ps` command to list all running containers on the host.
- Use the `docker stop` command to stop a running container.
- Use the `docker rm` command to remove a stopped container
- Use the `docker images` command to list all images on the host.
- Use `docker login` and `docker logout` command to authenticate and logout from a Docker registry

These tasks involve basic and common operations that can be used to manage images and containers. They will help you to get familiar with the Docker command-line interface and understand how to run and manage simple containerized applications.

You can Post on LinkedIn and let us know what you have learned from this task by #90DaysOfDevOps Challange. Happy Learning :)
