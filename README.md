[![CircleCI](https://circleci.com/gh/ahosny333/udacity_devops_capstone_project/tree/main.svg?style=svg)](https://circleci.com/gh/ahosny333/udacity_devops_capstone_project/tree/main)
# udacity_devops_capstone_project

This is my Udacity final project for the Cloud DevOps Nanodegree and I try to use all I learnt.

## Project details

This project was created to show the use of a CI/CD pipeline to create a simple app written in python to show 'Hello ...' message when receiving request.
Docker images were pushed to Docker hub, Hadolint was installed to lint the dockerfile, connect to the kubernetes cluster and deployed the docker image to it using rolling deployment.

Project steps:

- Create Makefile
- Create Dockerfile and Lint Dockerfile
- Build and upload Docker image to Docker hub
- Create cluster and node group in AWS EKS 
- Install kubectl
- deploy app to AWS EKS cluster
- Create CI/CD to run this commands after testing locally 


## Tools used

- Circleci for implementing the CI/CD
- GitHub for versioning
- AWS as the Cloud service
- aws cli
- Kubernetes to create clusters
- Docker containers deployed to the k8 clusters
