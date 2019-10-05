UNDERSTANDING CONTAINERS
Docker is primarily developed for Linux; it uses the resource isolation features of the Linux kernel.If you are familiar with the virtualization feature of Linux, then the concept of containerization is very easy to understand.

Containerization = Virtual partitioning feature of Linux + User friendly API
 


Virtual machine
*Applications require the full instance of the operating system.
*Hypervisor manages virtual partitions. It is a bit heavy and contributes to compute performance.
*Processes running via hypervisor execution cause overhead.

Containers
*Applications share the operating system with the server, so boot/shutdown is very fast.
*Docker daemon monitors and controls containers using Docker API or a command line.
*Processes run as native on the server enabling low CPU/memory overhead

