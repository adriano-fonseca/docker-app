 # Deploying a stack
 
[Here](https://github.com/adriano-fonseca/docker-app-from-base) I have talked about creating an application image from the a system base image which is basically a application server wuich contains the system's datasource. In this Project I have two docker-compose file the docker-compose-v3.yml can be used to deploy a stack with the command that follows: 

```shell
docker stack deploy --compose-file=docker-compose-v3.yml app-java
```

With the docker-compose.yml with the next command, we can simplify to run the application that in the [related project](https://github.com/adriano-fonseca/docker-app-from-base) we have run with docker commands:

```shell
docker compose up
```