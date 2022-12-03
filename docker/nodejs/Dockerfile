FROM node:10
WORKDIR /usr/src/app

COPY package*.json ./
RUN npm add express
RUN npm install
COPY . .
CMD [ "npm", "start" ]
