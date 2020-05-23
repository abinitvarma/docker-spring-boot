# docker-spring-boot
A sample project to run a simple spring boot projects as a docker container

This is a simple spring boot project with a simple rest endpoint. It has a dockerfile which is used by docker client to send specific instructions to Docker deamon on the instructions to be done.

# Run below command to create an image and run it as a container
docker build -t docker-spring-boot //This will create an image with a tag/name as docker-spring-boot
docker run -p 8080:8080 docker-spring-boot // This command will run the image as a container and expose the port 8080 of the container to the 8080 port of the host i.e. your system.
docker stop docker-spring-boot // This will stop the running container
