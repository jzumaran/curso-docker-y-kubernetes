# Specify a base image
FROM node:alpine

WORKDIR /home/app

# Install dependencies
COPY ./package.json ./
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]
