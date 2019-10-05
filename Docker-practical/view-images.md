PULLING DOCKER IMAGE FROM DOCKER HUB

$ docker pull {image-name}:{tag}

example

$docker pull alpine:3.6

$docker pull alpine:3.7

$docker pull alpine:ubuntu

![alt text](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(42).png)


**not specifing the tag will pull the latest stabe image**

to see the docker images on the local machine

$ docker images 

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(43).png)

TO see docker image id 

$ docker images --no-trunc

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(44).png)

To find a docker image of particular pattern

$ docker images --filter=reference='pattern'

eg

$ docker images --filter=reference='alpine'

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(46).png)

**this only seprates using pattern not tags**
