FROM node:18-alpine3.15 
RUN mkdir -p /home/MicroserviceProjectForDocker/eventbus
COPY /package.json /home/MicroserviceProjectForDocker/eventbus

WORKDIR /home/MicroserviceProjectForDocker/eventbus
RUN npm install
#copying folder
COPY . /home/MicroserviceProjectForDocker/eventbus
#entry point 
#only one entry point allowed
CMD ["node","index.js"]