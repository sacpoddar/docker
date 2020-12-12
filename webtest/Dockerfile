# specify a base image
FROM node:alpine

WORKDIR /usr/app
COPY ./ ./
# install dependencies
RUN npm install

EXPOSE 3000
# specify a command to run on container startup
CMD ["npm", "start"]
