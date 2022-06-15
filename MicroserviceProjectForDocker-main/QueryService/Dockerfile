FROM node
RUN mkdir -p /home/QueryService

COPY ./package.json /home/QueryService
WORKDIR /home/QueryService
RUN npm install

COPY ./ ./ 
#'copy the project files to image

EXPOSE 4004
CMD ["npm", "start"]