# MSSQL Docker Container

## Running the application to the default docker compose file 
* Create a network named mynet _$ docker network create mynet_
* install Docker Desktop latest version
* to start building the container image run docker compose up -d 

## Tag reference link
https://hub.docker.com/_/microsoft-mssql-server

## Code of Conduct RESPECT, RESPONSIBILITY, RELATIONSHIP

* Respect everyones idea.
* Respect leadership decision.
* Contribute openly, generously and unconditionally for the greater good of the product and the team.
* Make our product secure,functional and user-friendly while ensuring a strong and healthy team relationship.
* Respond and be available to answer the questions and needs of the members when required.
* Users and customers must be attended with utmost respect and consideration.
## Docker build the project command
* docker-compose up --build -d
## Docker show the container
* docker-compose ps //to show what docker app running if show (exist-1) the file not running
## Docker run auto restart
* docker run -d --restart always myimage:latest

