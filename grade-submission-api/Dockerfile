## Base Image
FROM node:14
## Working Directory
WORKDIR /app
## Install Dependencies
COPY package*.jason .

RUN npm install
## Copy Source code
COPY . .
## Expose container port
EXPOSE 3000
## Commands to execute application
CMD ["node","app.js"]