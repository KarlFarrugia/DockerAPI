# DockerAPI
Docker Application published on Azure in a container

cd to cwd

# Create Docker Image

docker --version
docker build -t kfarrugia/dockerapi .
docker images

# Run Docker

docker run -p 8080:80 kfarrugia/dockerapi

# Stop Docker

docker stop 91388d18ab67

# Publish Docker to DockerHub

docker push kfarrugia/dockerapi

# Azure version http://karlsdockerapi.westeurope.azurecontainer.io/
