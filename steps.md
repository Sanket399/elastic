# Exacts steps of the project

Create a machine for this project. Atleast a t2.large
Install docker on that machine
    sudo apt-get install docker.io docker-compose-v2
Give permissions to docker
    sudo usermod -aG docker $USER
Refresh the group "docker"
    newgrp docker

Then he cloned his own repo (which was forked from the main ElasticFlix repo by Elastic themself). In which he had a ready script to deploy the dummy application and the full elastic stack in docker containers. 

The app running on port 3000.
