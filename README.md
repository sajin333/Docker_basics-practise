# Basic docker commands and its explanation

docker --version Displays the version of the Docker installed in the local machine

![](Images/docker_version.png)

docker info Displays the information about Docker

![](Images/docker_info.png)

docker pull Pulls or Downloads the Docker Image from Dockerhub
![](Images/downloading_docker_image.png)

docker images Shows the list of Docker Images
![](Images/docker_images.png)

docker ps Shows the list of active Docker containers
![](Images/active_container.png)

docker stop container id Stops the container
![](Images/stopping_container.png)

docker run -dp hostport:container port image id Builds the container locally using the mentioned image id
![](Images/running_docker_image_becoming_container_jupyternotebook.png)

docker container ls -a Displays all Docker containers(Both Inactive and active)
![](Images/listing_all_containers.png)

docker rm containerid   Deletes the mentioned Docker container
![](Images/deleting_container.png)

docker rmi -f image_name Deletes the Docker image
![](Images/deleting_docker_images.png)

docker build -t image_name . Build the docker image by referring Dockerfile
![](Images/building_docker_image.png)

docker run -dp hostport:containerport image_name Starts building the container 
![](Images/starting_container_fromthe_image_build.png)

![](Images/container_running_as_webpage.png)

docker build -t userprofile/imagename .   Creating Docker image in useraccount dockerhub(This image name can be anything, it refers to Dockerfile, Images will be build on Dockerfile configuration)
![](Images/docker_image_created_in_dockerhub_profile.png)

docker push userprofile/image_name:tag_name   Pushes the image to user's Dockerhub
![](Images/pushing_dockerimage_to_dockerhub.png)

![](Images/image_in_dockerhub.png)

Downloads the docker image to local system
![](Images/docker_pull.png)

docker logs -f containerid Shows the logs of the mentioned container
![](Images/docker_logs.png)

docker inspect containerid Shows detailed description of the mentioned container id
![](Images/docker_inspect.png)

# Task2

Pulling Docker Image "Hello world" from Dockerhub and storing it locally

![](Task2/pulling_helloworld_image.png) 



Running the docker image locally

![](Task2/Running_Hello_World_Docker_Image_locally.png) 


# Task3

Creating Hello world application
![](Task3/Hello_world_fastapi_application.png)

Creating Dockerfile configuration
![](Task3/dockerfile.png)

Building Docker Image
![](Task3/building_docker_image.png)

Running the Docker image to convert it as a container
![](Task3/starting_container_fromthe_image_build.png)

Container as a webpage created which can be accessed locally
![](Task3/container_running_as_webpage.png)

Pusing Docker images to useraccount Dockerhub
![](Task3/pushing_dockerimage_to_dockerhub.png)

Created Docker image in Dockerhub
![](Task3/image_in_dockerhub.png)

Docker image creation in Dockerhub useraccount profile
![](Task3/docker_image_created_in_dockerhub_profile.png)


