# docker-image
Create Docker image with Dockerfile.

DockerHub: <https://hub.docker.com/repository/docker/diltheyaislan/nginx-with-vim-test>

## Dockerfile
Install vim editor and publish a new index.html file for nginx

## Build image
`docker build -t diltheyaislan/nginx-with-vim-test:latest .`

## Run container
`docker run -d --name nginx-with-vim -p 80:80 diltheyaislan/nginx-with-vim-test`