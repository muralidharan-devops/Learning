#### Docker Registry
##### Image
```
    image:docker.io/nginx/nginx
    image:registry/user or account/image or repo
```
#### Private Registry
```
    docker login private-registry.io
```
#### Deploy Private Registry

```
docker run -d -p 5000:5000 --name registry registry:2
docker image tag my-image localhost:5000/my-image
docker push localhost:5000/my-image
docker pull localhost:5000/my-image
docker pull 192.168.56.100:5000/my-image
```