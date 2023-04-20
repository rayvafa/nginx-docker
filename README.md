# nginx-docker

#### Building the docker image
`docker build -t nginx-server .`

#### Starting the container
`docker run --name nginx-server -ti -p 80:80 -d nginx-server`

#### Starting a container with environment variables
`docker run -e "ENV_CONFIG=development" --name nginx-server -ti -p 80:80 -d nginx-server`

#### running bash on the running container
`docker exec -it b1d51ad6fd20 bash`

#### List of running containers
`docker ps`

#### List of docker images
`docker images`

#### Stopping specific container
`docker stop 6b395f52f472`

#### deleting a specific image
`docker rmi af5d33ee575b`
