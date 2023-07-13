# api_flask_case

### How to use docker image.
1. First, you need to install Docker on your system. You can download and install Docker from its official website.
2. To run Docker commands, you need to open terminal or command prompt.
3. To use the Docker image, you need to download it. You can type the `docker pull ysufemrlty/case3:latest` command  to download the image.
4. You can type the `docker container run --rm -p 80:5000 ysufemrlty/case3` command to run the Docker image.
-----
### Descriptions of commands
1. The `docker pull` command is used to download the Docker image from a Docker hub or other Docker image repository (registry). This command pulls the specified image into your local Docker environment, allowing you to use that image later.
2. The `docker container run` command is used to create and run a new Docker container from the Docker image. This command allows you to start a container based on the Docker image.
3. The `--rm` option will automatically delete the container after Docker runs the container. When the container is terminated or stopped, it is automatically cleaned by Docker when using the `--rm` option.
This option is useful when creating temporary containers or using Docker containers for temporary operations. When the container is finished, it is deleted so that it does not take up unnecessary space and leave no residue in the system.
4. The `-p 80:5000` option enables port forwarding between the Docker container and the host. This option allows an application running in a Docker container to forward requests to a specific port to a specific port of the host.
In this example, using the `-p 80:5000` option specifies that requests to port 5000 of an application running in a Docker container will be forwarded to port 80 of the host.
5. The `ysufemrlty/case3` we ​​type at the end of the commands is the name of our docker image.
