FROM node:alpine3.21
WORKDIR /app
COPY package*.json .
RUN npm install
COPY .  .
ENTRYPOINT [ "node", "server.js" ]
