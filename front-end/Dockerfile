FROM node:14.18-alpine

#  Create app directory
WORKDIR /usr/src/

#  Install dependencies
#  Copy both package.json and package-lock.json

COPY package*.json ./

RUN npm install

COPY ./ ./

EXPOSE 3000

CMD ["node", "App.test.js"]
