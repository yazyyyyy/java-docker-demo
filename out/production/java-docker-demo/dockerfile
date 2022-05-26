#base image
FROM openjdk:8

#create new app directory
RUN mkdir /app

#copy application files from host machine
COPY out/production/java-docker-demo/JavaExample.class /app

#set directory for setting future commands
WORKDIR /app

#run main class
CMD java JavaExample
