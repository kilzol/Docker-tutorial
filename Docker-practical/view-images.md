PULLING DOCKER IMAGE FROM DOCKER HUB
$ docker pull {image-name}:{tag}
example
$docker pull alpine:3.6
$docker pull alpine:3.7
$docker pull alpine:ubuntu
**not specifing the tag will pull the latest stabe image**

to see the docker images on the local machine
$ docker images 

TO see docker image id 
$ docker images --no-trunc
To find a docker image of particular pattern
$ docker images --filter=reference='pattern'

eg
$ docker images --filter=reference='alpine'
**this only seprates using pattern not tags**