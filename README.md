# aligator-tongue
Docker LAMP container.

Personal Strides to Learn Software Development

Step 0.0 - Purchase a computer, set up a Github account 


Step 0.1 - Create a new repository on Github site, then create a local repository on your computer

 
Step 0.2 - Verify that you are able to connect to Github via SSH
# Resources : https://docs.github.com/en/authentication/connecting-to-github-with-ssh


Step 0.3 - Connect your local repository to the Github repo
# Resources : https://gist.github.com/xirixiz/b6b0c6f4917ce17a90e00f9b60566278


Step 0.4 - Verify you are able to 'git push' a test document to the Github remote repo
# Resources : https://training.github.com/downloads/github-git-cheat-sheet.pdf


*___________________________________*

--> Docker-LAMP
# Resources : https://github.com/rhalp10/docker-lamp

--> This repository goal is to create a docker container and compose: Centos, Apache, PHP and PDO DBLIB, MySQL

Docker Compose
# Resource : https://docs.docker.com/compose/
Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. 

Step 1.0 - Create a docker-compose.yml file, that that file define two services - "web" and "db". 
The "web" service will use the Dockerfile for Apache/PHP container
The "db" service will use the Dockerfile for the MySQL container  
