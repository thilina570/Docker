
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
| `docker run <imageName>` | run a container from image |
| `docker run hello-world` |  |
| `docker ps` | running containers |
| `docker ps -a` | list all containers on the system |
| `docker stop ContainerID` | stop running container |
| `docker rm ContainerID ` | remove stoped containers |
| `docker images` | list of  images |
| `docker images -q` | return only the image ID’s of the images |
| `docker rmi <ImageID>` | removing  images |

The base command for the Docker CLI - 2.
|  |  |
|--|--|
| `docker run ubuntu sleep 10` |  |
| `docker exec <container> cat /etc/hosts` |  |
| `docker run --name <custom name> <image name>` |  |

The base command for the Docker CLI - 3.
|  |  |
|--|--|
| `docker run ubuntu:18.04` | run specific version |
| `docker run -d centos sleep 1000` | -d for detach : run in background |
| `docker run attache <containerId>` | attache to container oposite of -d |
| `docker run -i <custom name> <image name>` |  | 
| `docker run -p 3306:3306 mysql` |  |
| `docker run -v host/data:container/data mysql` | volume mapping |

|  |  |
|--|--|
| `docker top ContainerID` |  |
| `docker stats ContainerID ` |  |
| `docker pause ContainerID ` | |
| `docker unpause ContainerID` | |
| `docker kill ContainerID` | |
| `docker container logs <containerId>` | |
| `docker container top <containerId>` | |
| `docker container inspect <containerId>` | view  |
| `docker container stats` | view  |
| `docker container run -it --name <containerName> <image> bash` | start new container interactively  |
| `docker container start -ai ubuntu` | view  |
| `docker container exec -it mysql bash` | run additional command in existing container  |

