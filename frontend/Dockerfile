FROM node:18-alpine3.15 
RUN mkdir -p /home/MicroserviceProjectForDocker/frontend
COPY /package.json /home/MicroserviceProjectForDocker/frontend

WORKDIR /home/MicroserviceProjectForDocker/frontend
RUN npm install
#copying folder
COPY . /home/MicroserviceProjectForDocker/frontend
#entry point 
#only one entry point allowed
CMD ["npm", "start"] 