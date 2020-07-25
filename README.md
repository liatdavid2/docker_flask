# python flask rest app on docker container 

steps - 
1. The docker build command builds Docker images from a Dockerfile and a “context”. A build’s context is the set of files located in the specified PATH or URL. 

command:
docker build -t my_docker_flask:latest .
2. The docker run command first creates a writeable container layer over the specified image, and then starts it using the specified command.

command:
docker run -d -p 5000:5000 my_docker_flask:latest
