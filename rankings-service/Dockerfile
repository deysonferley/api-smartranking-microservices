FROM node:12.16-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN yarn install

COPY . .

RUN yarn build

CMD ["node", "dist/main"]


