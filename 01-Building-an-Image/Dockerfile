FROM node:alpine 
#this is the base image for node and alpine is the bare bone version

WORKDIR /usr/app
#instead of copying in root dir use this dir

COPY package.json  .
# created a copy of the files/folders(where docker file lies) in the root dir
# the first . is for root dir
# the seoncd . is for the workdir

RUN npm install
#creates a intermediate constainer and takes it end environment and updates the image itself and shuts the container

COPY .  .
# created a copy of the files/folders(where docker file lies) in the root dir
# the first . is for root dir
# the seoncd . is for the workdir

CMD ["npm","run", "start"]
#tells our image to store the command somewhere in the image