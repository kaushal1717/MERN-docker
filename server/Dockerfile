FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

run npm i

COPY . .

EXPOSE 5000

CMD [ "npm", "run", "dev" ]