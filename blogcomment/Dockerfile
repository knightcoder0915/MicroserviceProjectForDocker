FROM node:18-alpine3.15 
RUN mkdir -p /home/MicroserviceProjectForDocker/blogcomment
COPY /package.json /home/MicroserviceProjectForDocker/blogcomment

WORKDIR /home/MicroserviceProjectForDocker/blogcomment
RUN npm install
#copying folder
COPY . /home/MicroserviceProjectForDocker/blogcomment
#entry point 
#only one entry point allowed
CMD ["node","index.js"]