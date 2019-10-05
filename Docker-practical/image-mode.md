<h3> The  basic command we used  till now<h3>

>$ docker run {iamge-name}{tag}

but in this mode the image performs its task and then get deleted, so if we want the image to stay after performing the task we need to 
use intractive mode i.e we need to open the image in intractive mode :-

>$ docker run itd {image name}

* it: interactive mode
* d : Daemon or detached mode: won't open container in front but opens it as a daemon (background process)

**to see running docker container**

>$ docker ps

**to stop a running container**

>$ docker stop {container name, container id or first three letters of container id} 

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(47).png)

stop only stoped its execution it is still present in our local machine so we can delete it using 

>$ docker rm {container name or id or first three letters of id}

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(48).png)

to enter a daemon container to intractive mode use 
>$ docker attach {Image ID or first three letters} 
 
 and to exit it use 
>#exit

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(49).png)

**To exit a container in up mode press
>ctr + P + q

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(50).png)

