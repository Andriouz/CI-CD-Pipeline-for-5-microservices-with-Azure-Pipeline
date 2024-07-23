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

Step 3 —  Create an Agent Pool: an instance that the Azure Pipeline will run on and configure the Azure pipeline with the Agent Pool

Step 4 — Create an Azure Pipeline to build and push the images to Azure Container Registry

Step 5 — Create a Docker file for each microservices: Python, Node.js & .Net

Step 6 — Create Azure Pipeline script for each microservices: Python, Node.js & .Net

Step 7 — Docker Image Build and Push to the container registry

Step 8 — Create a k8s Deployment.yml file for each microservice

Step 9 — Azure Kubernetes Service Set Up

Step 10 — ArgoCD Set Up

Step 11 - Created a shell script to start ArgoCD when a new image is built: A developer commits a change to the Repo, and a new image is built.

Step 12 - Continous Deploy the Kubernetes Cluster using ArgoCd

## Now, lets get started and dig deeper into each of these steps :-

**Step 1 — Migrate Web app source code from GitHub Repository to Azure Repository**

![9](https://github.com/user-attachments/assets/6a3f0381-6225-4436-ba65-8a1f03c2df28)

**Step 2 — Launch an Azure Virtual Machine. Use the image as Ubuntu. You can create a new key pair or use an existing one. Enable HTTP and HTTPS settings in the Security Group**

![111](https://github.com/user-attachments/assets/c9a2db4d-5637-43c0-a55b-c385fe776c50)

**Step 3 —  Create an Agent Pool: an instance that the Azure Pipeline will run on**

![azureagentpipeline](https://github.com/user-attachments/assets/814bec2c-788f-4b5a-a54b-b99f12db95b8)

**Step 4 — Create an Azure Pipeline to build and push the images to Azure Container Registry**

![222](https://github.com/user-attachments/assets/007b2c11-a4c5-4cae-8a5e-4e04ec339d2a)

![213](https://github.com/user-attachments/assets/6769a82f-d317-4d59-a007-068f03066e07)


**Step 5 — Create a Docker file for the microservices: Python, Node.js & .Net**

![333](https://github.com/user-attachments/assets/d0b25a5f-b927-42e6-a82e-ec2a587634fd)

**Step 6 — Create Azure Pipeline script for each microservices: Python, Node.js & .Net**

![124](https://github.com/user-attachments/assets/bd51ee62-69c2-4f79-b8ea-a46521adb17c)

![125](https://github.com/user-attachments/assets/fe83f621-3102-4893-9505-113162f9c733)

![123](https://github.com/user-attachments/assets/6bef824c-e1d5-4d25-b427-507099530f85)

**Step 7 — Docker Image Build and Push to the container registry**

![231](https://github.com/user-attachments/assets/cfc550b6-2a4c-440f-b8dd-bbaf48028c54)

![231](https://github.com/user-attachments/assets/c97e32e0-90ba-4c1a-8536-78cac3d347f5)

![232](https://github.com/user-attachments/assets/a463a711-25d8-44ae-92bb-9f7f95bcf146)

![3](https://github.com/user-attachments/assets/39f2e326-5d29-458f-8c65-0c43083288d5)

**Step 8 — Create a k8s Deployment.yml file for each microservice**

![311](https://github.com/user-attachments/assets/82234acc-dcb8-43d0-9e4a-8e9b27d67866)

**Step 9 - Azure Kubernetes Service Set Up**

![212](https://github.com/user-attachments/assets/c934f5f8-24f2-43ea-9075-ad989c52df26)

**Step 10 — ArgoCD Set Up**

![121](https://github.com/user-attachments/assets/e568a51a-83af-4939-a668-28c5092711e7)

**Step 11 - Created a shell script to start ArgoCD when a new image is built: A developer commits a change to the Repo, and a new image is built.**

![126](https://github.com/user-attachments/assets/478af9a1-1785-480f-aed0-5bcba33e604a)

**Step 12 -The 5 Microservices deployed to the Kubernetes Cluster using ArgoCd**

![6](https://github.com/user-attachments/assets/3dad01da-a260-4861-94ce-c0ce07b3090c)

![55](https://github.com/user-attachments/assets/78846012-7eff-4d57-b4b0-821f9d0d4850)

![7](https://github.com/user-attachments/assets/1bd712a6-83d6-4b71-adef-63af9ca084d9)


















