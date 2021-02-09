Deploying Sock Shop on any Kubernetes cluster
This explains how to deploy the Sock Shop onto any existing Kubernetes cluster.

Pre-requisites
Create a Kubernetes linux cluster. For instance, see these examples:
AWS - KOPS
Azure - Azure Container Service
Google Cloud - Google Container Engine
Install and configure kubectl to connect to the cluster
Deploy Sock Shop

steps:To Deploy Socks Shop
=====
1)Clone the microservices-demo repository
git clone https://github.com/GoogleCloudPlatform/microservices-demo.git


2)Go to the deploy/kubernetes folder

3)kubectl create namespace sock-shop

4)kubectl apply -f complete-demo.yaml
