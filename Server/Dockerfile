
FROM node:lts-alpine

WORKDIR /App

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 9000

CMD [ "npm", "start" ] 





