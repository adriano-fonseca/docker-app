# Deploying application Stack in Swarm Cluster
 
[Here](https://github.com/adriano-fonseca/docker-app-from-base) I have talked about creating an application image from a system base image, which is basically a application server which contains the system's Datasource and the required postgres driver. In this Project I have two docker-compose file the docker-compose-v3.yml can be used to deploy a stack with the command that follows: 

```shell
docker stack deploy --compose-file=docker-compose-v3.yml app-java
```

With the docker-compose.yml, we can simplify to run the application that in the [related project](https://github.com/adriano-fonseca/docker-app-from-base) we have run with docker commands:

```shell
docker compose up
```