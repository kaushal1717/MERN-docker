FROM node:20-alpine

WORKDIR /app

COPY package*.json ./

RUN command npm i

COPY . .

EXPOSE 5000

CMD [ "npm", "run", "dev" ]