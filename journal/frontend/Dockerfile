FROM node:10-alpine

COPY package-lock.json /package-lock.json

RUN npm install && npm install --save redis@2.8.0

COPY server.js /server.js

CMD node /server.js