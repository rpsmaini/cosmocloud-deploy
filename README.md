# cosmocloud_deploy
This repo is meant for selection purposes in the organization
Here is the further description of the project:
In this project we will be creating 3 services in kubernetes using helm charts.
3 services consist of a frontend, backend and Redis as database respectively.
Prerequisites
Before you clone this repo make to have following softwares:
    1. Kubectl(Kubernetes CLI)
    2. Helm
    3. Docker
    4. Kubernetes(Minikube)
Once you install the Softwares:
    1. Clone this repo to your machine
    2. Once the repo is cloned open the terminal and type "cd cosmocloud_deployment"
    3. Then start your minikube using "minikube start" command
    4. Once minikube is running to deploy the app type "helm install testapp ./cosmocloud_deploy --atomic --timeout 30s"
