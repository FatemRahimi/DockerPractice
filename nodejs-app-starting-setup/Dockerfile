FROM node

WORKDIR /app

Copy package.json /app

RUN npm install

COPY . /app

EXPOSE 80
   
CMD ["node", "server.js"]


# in this project we understood we dont need to 
#have npm insall after each changes in side the codes , when we want 
#to change the codes the docker catch should run just
#copy ./app just should make image , 
#before that we put 
#Copy package.json /app

#RUN npm install
#after that 
#docker build .
#docker images
#docker run ps
#docker run -p 3000:80 image id 

#some times you need to start your container again
#if you type docker ps maybe you cant find a new #container 
#in you type docker ps --help you can find many command to help you

#docker start the ame of container exist in ps -a


#you can add detached or attached in your command using -d , 

#By default, if you run a Container without -d, you run in "attached mode".
#Attaching to an already-running Container

#If you started a container in detached mode (i.e. with -d), you can still attach to it afterwards without restarting the Container with the following command:

#docker attach CONTAINER
#attaches you to a running Container with an ID or name of CONTAINER.

#If you want to see container logs without getting stuck, use:
 #   docker logs -f f09023d31af8
  #  If you want the container to keep running in the background and return to the terminal, use:
   # docker run -p 3000:80 -d f09023d31af8

   #fatemehrahimi@fatemehRahimis-MacBook-Pro nodejs-app-starting-setup % docker logs 5a7302548b89
  # i am glad to see you 
   #my father
   #fatemehrahim

   #fatemehrahimi@fatemehRahimis-MacBook-Pro nodejs-app-starting-setup % docker start 5a7302548b89 
#5a7302548b89
#fatemehrahimi@fatemehRahimis-MacBook-Pro nodejs-app-starting-setup % docker attach 5a7302548b89 
#hi mary








