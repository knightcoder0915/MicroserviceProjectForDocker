FROM node:18-alpine3.15 
RUN mkdir -p /home/MicroserviceProjectForDocker/blogpost
COPY /package.json /home/MicroserviceProjectForDocker/blogpost

WORKDIR /home/MicroserviceProjectForDocker/blogpost
RUN npm install
#copying folder
COPY . /home/MicroserviceProjectForDocker/blogpost
#entry point 
#only one entry point allowed
CMD ["node","index.js"]