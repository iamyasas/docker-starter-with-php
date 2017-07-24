# Getting started with Docker

Steps to try out the sample

1) cd 'docker-starter-with-php' directory

2) Build docker image in the same directory as hello-world
   
   docker build -t hello-world .  
   
3) Run the image in a container(Forward port 80 of the host server to port 80 of the container) 
   
   docker run -p 80:80 hello-world
   
4) Browse localhost
