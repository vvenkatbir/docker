# Nodejs web app

Express app with handlebars view engine.
Has a docker file with all the intructions to run the dockerized application as a container with a simple hello Message printed
have the run the following commands to run the application locally 
--> install
after the npm install is success 
-->node app.js

will launch the app at http://localhost:8080

Docker Commands:

a)docker build -t vvasant3/docker-example:first-container. : This cammand build the docker image by iterating through the steps in the dockerfile of this code base

b)docker push vvasant3/docker-example:first-container will push this image to the docker hub  https://hub.docker.com/repository/docker/vvasant3/docker-example

c)docker container run -d --name fc -p 8000:8080 vvasant3/docker-example:first-container this command will pull the image vvasant3/docker-example:first-container from the docker hub if it is not available in your local and run the image as a container 

d) docker container start will start the container 

e) docker container stop will stop the container 

f) docker container ls -a will list all the running containers

g) docker images will list all the images 

i)docker image rm <imageID> will remove the specified images 
  
j)docker container rm <container_ID> will delete the stopped container use d and e commands to start and stop the container
