FROM node:latest
WORKDIR /app
COPY package.json ./
EXPOSE 3000
COPY . .
RUN npm install
RUN npm install nodemon -g
CMD [ "nodemon", "server.js" ]
