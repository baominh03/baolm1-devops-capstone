[![CircleCI](https://dl.circleci.com/status-badge/img/gh/baominh03/baolm1-devops-capstone/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/baominh03/baolm1-devops-capstone/tree/main)

# baolm1-devops-capstone

## Set Up Pipeline

1. Create Github repository with project code: https://github.com/baominh03/baolm1-devops-capstone

2. Use image repository to store Docker images: https://app.circleci.com/pipelines/github/baominh03/baolm1-devops-capstone
![build-push-docker](images/build-push-docker.png)
![pipeline](images/circleci-pipeline.png)


## Build Docker Container

1. Execute linting step in code pipeline: 
![lint](images/lint.png)

2. Build a Docker container in a pipeline: 
![build-container](images/build-container.png)

## Successful Deployment  

1. The Docker container is deployed to a Kubernetes cluster: ![deployed-kubernetes-cluster](images/deployed-kubernetes-cluster.png)

2. Use Blue/Green Deployment or a Rolling Deployment successfully: 
![deployed-kubernetes-cluster](images/deployed-kubernetes-cluster.png)
![pipeline](images/circleci-pipeline.png)