# CI-CD-Pipeline-for-Voting-5-microservices

A simple distributed application running across multiple Docker containers.

![architecture excalidraw](https://github.com/user-attachments/assets/b7f712a9-99db-4b48-bc0f-a10d7a0e5444)

- A front-end web app in **Python** which lets you vote between two options

- A **Redis** which collects new votes

- A **.NET worke**r which consumes votes and stores them in…

- A **Postgres database** backed by a Docker volume

- A **Node.js** web app which shows the results of the voting in real time
