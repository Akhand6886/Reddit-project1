# Reddit Clone App on Kubernetes
This project demonstrates how to deploy a Reddit clone app on Kubernetes and expose it to the world using Minikube as the cluster.

## Prerequisites
Before you begin, you should have the following tools installed on your local machine: 

- Docker
- Minikube cluster ( Running )
- kubectl
- Git

# For Docker Installation
sudo apt-get update \n
sudo apt-get install docker.io -y \n
sudo usermod -aG docker $USER && newgrp docker \n

---------------
minikube.sh
---------------
# For Minikube & Kubectl
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64  \n
sudo install minikube-linux-amd64 /usr/local/bin/minikube  \n

sudo snap install kubectl --classic \n
minikube start --driver=docker \n