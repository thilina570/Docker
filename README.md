# docker

The 7 Types of Virtualization
	
 - OS Virtualization—aka Virtual Machines
 - Application-Server Virtualization
 - Application Virtualization
 - Administrative Virtualization
 - Network Virtualization
 - Hardware Virtualization
 - Storage Virtualization

|  |  |
|--|--|
| `docker` | Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers |
| `Docker Hub` | Docker Hub is a registry service on the cloud that allows you to download Docker images that are built by other communities. |
| `Docker Image` | In Docker, everything is based on Images. An image is a combination of a file system and parameters. |
| `Docker Container` | Containers are instances of Docker images that can be run using the Docker run command. |
# docker-cheatsheet
The base command for the Docker CLI.
|  |  |
|--|--|
| `docker --version` |  |
| `docker info` |  |
| `docker run hello-world` |  |
| `docker run --name <custom name> <image name>` |  |
| `docker images` | list of Docker images |
| `docker images -q` | return only the Image ID’s of the images |
| `docker rmi <ImageID>` | Removing Docker Images |
| `docker ps` | return the currently running containers |
| `docker ps -a` | list all of the containers on the system |
| `docker top ContainerID` |  |
| `docker stop ContainerID` |  |
| `docker rm ContainerID ` |  |
| `docker stats ContainerID ` |  |
| `docker pause ContainerID ` | |
| `docker unpause ContainerID` | |
| `docker kill ContainerID` | |
