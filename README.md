# Lekir Framework - Docker Edition
Here host the pre-built Lekir Framework docker image along with docker-compose.yml template. Some modifications had been made from the original build for containerization purposes.

For more information about Lekir Framework, visit the [Lekir Repo](https://github.com/firdauskhairuddin/lekir) by [Firdaus Khairuddin](https://github.com/firdauskhairuddin)


##  Deployment

1. Make sure to install docker and docker compose on your pc

2. Run the following command in the same directory of `docker-compose.yml`

| :zap:        `docker compose up`   |
|-----------------------------------------|


3. Access lekir web panel via http://localhost:13370 or http://127.0.0.1:13370

##  Information 
By default, the docker images will bind to port 3306, 13370 & 4444 on your localhost.
13370 - web
3306 - mysql
4444 - port for reverse shell or etc

| :warning: Make sure|
|:---------------------------|
| No services are running on the mentioned ports      |


## Docker troubleshooting

 - List running container
`docker ps`
 - Stopping running container
`docker stop <CONTAINER_ID>`
 - List docker images
`docker images`
 - Delete docker images
`docker rmi <IMAGE_ID>`
 - Force delete docker images
`docker rmi <IMAGE_ID>`
 - Accessing shell
`docker ps -it <CONTAINER_ID> /bin/bash`
`docker ps -it <CONTAINER_ID> /bin/sh`

## Credit
Much thanks to [Firdaus Khairuddin](https://my.linkedin.com/in/firdauskhairuddin) for creating this project. 
I do not hold any responsibility on the project. All rights go to the rightful creator.
May Malaysia be stronger.
#majulah malaysiaku @firdauskhairuddin
