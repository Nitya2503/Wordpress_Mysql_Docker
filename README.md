# Wordpress_Mysql_Docker

This is a simple setup of Wordpress with Mysql database using docker compose file.

# Introduction:-
Wordpress is a content management system that provides the ability to publish, edit, modify, organize, delete and maintain content all in one central space.
WordPress needs two components to work on your web server: PHP and MySQL.

# Pre-configurations needed:
You will require Docker and Docker Compose to be installed in your system. To download follow the link:
For docker:- https://www.docker.com/products/docker-desktop
For docker compose:- https://docs.docker.com/compose/install/

#  docker-compose file:-
Create a file named as docker-compose.yaml. After creating the file you should define version, all the services, container names, volumes and ports. I have attached docker-compose file for reference.

# For building the Images and containers:-
After creating docker compose file. use command 
``` docker-compose up -d ``` or  ``` docker-compose build ``` commands to create the conatiners. This command will automatically pull images from the docker hub.

# Output:-
Just go to your browser and type > localhost:8000/ and all set Famous five minute setup of wordpress will be there just fill up some details and get started.


# For closing all the containers:

Just Use command ```docker-compose down``` in your terminal, all running containers which are associated with your docker-compose file will get stopped.


