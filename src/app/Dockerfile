FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

COPY app.js ./

RUN npm install

RUN npm start

EXPOSE 8080