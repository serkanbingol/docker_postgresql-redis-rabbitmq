

**Working with Docker-Compose**

- In the root directory of the project run "**docker-compose up**" command.
- Wait all containers to start.
- To run continuously all containers run  "**docker-compose up -d**" command.
- To shut-down all containers run  "**docker-compose down**" command.



**Table for credentials**


|Container |         Port         |Username|Password|
|:--------:|:--------------------:|:------:|:------:|
|  Redis   |http://localhost:6379 | -----  | -----  |
| RabbitMQ |http://localhost:5672 | -----  | -----  |
| RabbitMQ |http://localhost:15672| guest  | guest  |
|PostgreSql|http://localhost:5432 |postgres|postgres|


**Check containers status**

- After containers is up run "**docker container ls**" to see their status
- run "**telnet localhost 5672**" , "**telnet localhost 15672**"  , "**telnet localhost 6379**" ,"**telnet localhost 5432**"  to get response from containers

## Compose Up Sample Screencast

![compose-up.gif](https://github.com/bilgeadamdev/docker_postgresql-redis-rabbitmq/blob/master/images/up_postgresql-redis-rabbitmq.gif)

## Compose Down Sample Screencast

![compose-down.gif](https://github.com/bilgeadamdev/docker_postgresql-redis-rabbitmq/blob/master/images/down_postgresql-redis-rabbitmq.gif)


