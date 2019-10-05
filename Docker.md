WHAT IS DOCKER 
Docker is an open source software platform to create, deploy and manage virtualized application containers on a common operating system (OS), with an ecosystem of allied tools. Docker Inc., the company that originally developed Docker, supports a commercial edition and is the principal sponsor of the open source tool.
Docker is a tool that packages, provisions and runs containers independent of the OS. Container technology is available through the operating system: A container packages the application service or function with all of the libraries, configuration files, dependencies and other necessary parts to operate. Each container shares the services of one underlying operating system.
Docker was created to work on the Linux platform, but has extended to offer greater support for non-Linux operating systems, including Microsoft Windows and Apple OS X. Versions of Docker for Amazon Web Services (AWS) and Microsoft Azure are available.
DOCKER ADVANTAGES AND DISADVANTAGES
Docker has emerged as a de facto standard platform that allows users to quickly compose, create, deploy, scale and oversee containers across Docker hosts. Docker allows a high degree of portability so that users can register and share containers over various hosts in private and public environments. Docker benefits include efficient application development, lower resource use and faster deployment compared to VMs.

There are also potential challenges with Docker. The sheer number of containers possible in an enterprise can be difficult to manage efficiently. Security can also pose a problem. Despite excellent logical isolation, containers share the host's operating system. An attack or flaw in the underlying operating system can potentially compromise all of the containers running atop the OS. Some organizations run containers within a VM, although containers do not require virtual machines.
Containerization is quite an old concept, but Docker brings several new things to the table that the earlier technologies did not.

*Docker is designed to incorporate most of the recent DevOps tools like Chef, Puppet, Ansible, Jenkins etc.
*Docker makes it possible for developers to replicate their production environments easily as ready-to-run container applications and thus they can work more efficiently.
*Docker enables flexibility and portability by allowing applications to run on laptops, in-house servers, public cloud, private cloud etc. Managing and deploying applications is much easier.
*Docker implements a high-level API to provide lightweight containers that run processes in isolation.
Nowadays, its mainly used by developers and system administrators to build, ship and run distributed applications in association with DevOps.

DOCKER ARCHITECTURE
 

Docker client (docker) is interface that allows communication between the user and the Docker daemon using REST API (http request).

Docker daemon (docker) is running on host machine handling requests for services (for example, building and storing images, creating, running and monitoring containers).
Docker registry is backup of Docker container images with public and private access permissions.
Docker file contains instructions to build a Docker image.
Docker image is a read-only template with instructions for creating a Docker container (when the image is built then it is brought to life as a container).
Docker container is running applications. There can be multiple containers running based on the same image. One can create, start, stop, move or delete using Docker API or command line.

It is also important to note that Docker uses the below operating system features:
*Namespaces make sure a process running in a container cannot see or affect processes running outside the container.
*Control Groups used for resource accounting and limiting key functionality.
*UnionFS (FileSystem) serves as building blocks of containers. It creates layers and enables Docker with lightweight and fast features.
