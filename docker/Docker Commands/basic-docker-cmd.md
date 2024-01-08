##Basic Docker Commands

#####Run-start a container
```docker run nginx```

#####PS - List containers
```docker ps ```
```docker ps  -a```

#####STOP -stop acontainer

```
docker ps
```
```docker stop < docker image name or id>```

#####Rm -Remove a container
```docker rm <docker docker container name or id```
 
#####Images - List images
```docker images```
#####rmi - remove images
> Delete all the dependent container to remove the image 
```docker rmi <image name>```
#####Pull- Download an image

```docker pull < image  name or url ```
> the pull command only pull image in the base machine


#####Append a command 
```docker run ubuntu```
> It will and exits the container.

```docker run ubuntu slepp 5```

#####Exec - execute a command
```docker exec  < container name or id >```

##### Run -attch and detech
```docker run nginx```
> The above running in attch mode 

```docker run -d nginx```
> The above running container in detach mode