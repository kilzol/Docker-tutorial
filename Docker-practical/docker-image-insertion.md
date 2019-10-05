<h1>CREATE A DOCKER IMAGE AND UPLOAD IT TO DOCKER HUB

1.to create an image  
>vi Dockerfile
>#FROM alpine
>#Run apk upgrade
>#Run apk add git

press esc +:wq to exit the editor

2.Login to your account using
>docker login

3.build your docker image using docker file
>$ docker build -t {docker image name} .

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(51).png)

4.Create tag for your docker image

>$docker tag <<image name>> {docker hub username}/{docker image name you want on remote repo:version}

eg
>$docker tag kil kilzol007/kil:1.0 

to view image 
>$docker ls

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(52).png)

5.Push the image to docker hub
>$ docker push <<imagename:version>>

eg
>$docker push kilzol007/kil:1.0

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(55).png)

![alt](https://github.com/kilzol/Docker-tutorial/blob/master/Docker-practical/Images/Screenshot%20(54).png)



![alt]()
