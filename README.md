# container_from_scratch
Building a container from scratch

## Build the Contianer Yourself and Push to Docker Hub

# Build Image

# List docker images

docker image ls

# Run newly built container
docker run -it hello-duke-cli-210 python app.py --name "Big John"

# Push to Docker Hub


# Run it yourself 

docker pull noahgift/cloudapp:latest
docker run -it noahgift/cloudapp bash 

#then run python app.py --help

# Pass in a command
docker run -it noahgift/cloudapp python app.py --name "Big John"
#the output
Hello Big John!


# Push to Amazon ECR

