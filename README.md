# Reddit Clone App on Kubernetes
This project demonstrates how to deploy a Reddit clone app on Kubernetes and expose it to the world using Minikube as the cluster.

## Prerequisites
Before you begin, you should have the following tools installed on your local machine: 

- Docker
- Minikube cluster ( Running )
- kubectl
- Git

# For Docker Installation
sudo apt-get update <br>
sudo apt-get install docker.io -y <br>
sudo usermod -aG docker $USER && newgrp docker <br>

---------------
minikube.sh
---------------
# For Minikube & Kubectl
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64  <br>
sudo install minikube-linux-amd64 /usr/local/bin/minikube  <br>

sudo snap install kubectl --classic <br>
minikube start --driver=docker <br>


-----------------
aws cli
----------------
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"  <br>
unzip awscliv2.zip  <br>
sudo ./aws/install  <br>
