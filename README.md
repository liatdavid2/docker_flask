# python flask rest app on docker container - run the following  commands

docker build -t my_docker_flask:latest .

docker run -d -p 5000:5000 my_docker_flask:latest
