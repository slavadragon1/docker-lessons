FROM node:20.5.1-alpine

ENV NODE_ENV=production

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

# RUN npm install -g serve

COPY . .

RUN npm run build

RUN nginx