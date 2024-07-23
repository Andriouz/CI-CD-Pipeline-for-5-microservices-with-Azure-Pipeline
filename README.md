# CI-CD-Pipeline-for-Voting App with-5-microservices-using Azure Pipelines, Azure Repo, Azure Container Registry, Azure Kubernetes Service, Docker, GitOps, ArgoCD

**Real-Time DevOps Pipeline for a Web App built with Python, Redis, .Net, Postgres Database & Node.js**

A simple distributed application running across multiple Docker containers.

![architecture excalidraw](https://github.com/user-attachments/assets/b7f712a9-99db-4b48-bc0f-a10d7a0e5444)

- A front-end web app in **Python** which lets you vote between two options

- A **Redis** which collects new votes

- A **.NET worke**r which consumes votes and stores them in…

- A **Postgres database** backed by a Docker volume

- A **Node.js** web app which shows the results of the voting in real time
  

## CI/CD Pipeline Architecture

![Untitled design (2)](https://github.com/user-attachments/assets/bea02fd6-a917-4dfd-8555-bc407dac179a)

Steps:

Step 1 — Migrate Web app source code from GitHub Repository to Azure Repository

Step 2 — Create an Ubuntu virtual machine on Azure

Step 3 — Create an Azure Pipeline to build and push the images to Azure Container Registry

Step 4 — Create an Agent Pool: an instance that the Azure Pipeline will run on

Step 5 — Configure the Azure pipeline with the Agent Pool

Step 6 — Create a Docker file for each microservices: Python, Node.js & .Net

Step 7 — Create Azure Pipeline script for each microservices: Python, Node.js & .Net

Step 8 — Docker Image Build and Push to the container registry

Step 9 — Create a k8s Deployment.yml file for each microservice

Step 10 — Azure Kubernetes Service Set Up

Step 11 — ArgoCD Set Up

Step 12 - Created a shell script to start ArgoCD when a new image is built: A developer commits a change to the Repo, a new image is built.

Step 13 - Continous Deploy the Kubernetes Cluster using ArgoCd

## Now, lets get started and dig deeper into each of these steps :-

Step 1 — Launch an Azure Virtual Machine. Use the image as Ubuntu. You can create a new key pair or use an existing one. Enable HTTP and HTTPS settings in the Security Group

![111](https://github.com/user-attachments/assets/c9a2db4d-5637-43c0-a55b-c385fe776c50)

![azureagentpipeline](https://github.com/user-attachments/assets/814bec2c-788f-4b5a-a54b-b99f12db95b8)
