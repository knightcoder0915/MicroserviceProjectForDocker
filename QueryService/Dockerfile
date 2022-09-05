FROM node:18-alpine3.15 
RUN mkdir -p /home/MicroserviceProjectForDocker/QueryService
COPY /package.json /home/MicroserviceProjectForDocker/QueryService

WORKDIR /home/MicroserviceProjectForDocker/QueryService
RUN npm install
#copying folder
COPY . /home/MicroserviceProjectForDocker/QueryService
#entry point 
#only one entry point allowed
CMD ["node","index.js"]