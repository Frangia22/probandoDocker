FROM node:16.15.1-alpine3.16

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD npm run dev