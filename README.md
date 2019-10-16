# How to?

## Pull existing image
`docker pull nginx:alpine`

## build image 
`docker build -t my-nginx  .`

## See list of images
`docker images`

## Run the image in a container 
`docker run -d -p 8080:80 my-nginx`

`-d` will run in detached mode. 

## See list of running containers
`docker ps`

## See list of all containers
`docker ps -a`

## Stop a container
`docker stop <containerID>`

## Remove a container
`docker rm <containerID>`

## Remove an image
`docker rmi <imageID>`

