####Docker Network
![alt Name](Default-Network.png)
#### User-defined networks
```
docker network create \
  --driver bridge \
  --subent 182.18.0.0/16
  custom-isolated-network
```
List Docker Network
```docker network ls```

![alt Name](user-defined-network.png)

#####Inspect network
```docker inspect <container id></container>```

#####Embedded DNS
![alt Name](EmbeddedDNS.png)