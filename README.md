# Docker node server

# About the project

It is a basic aplication of a dockerized node server

# Technologies used

-   NodeJs
-   Docker

# How to run the project

Prerequisites: Have docker installed on your machine

```bash
# Clone repository
git clone https://github.com/poring86/docker-node-server.git

# Enter the project folder
cd docker-node-server

# Build docker image
docker build -t node-server .

# Run docker container
docker run -p 8080:8080 node-server

# Acess the server
Paste "http://localhost:8080" on your browser

```

# Autor

Matheus de Lino Ferreira

https://www.linkedin.com/in/matheus-de-lino-ferreira-7a3929187/
