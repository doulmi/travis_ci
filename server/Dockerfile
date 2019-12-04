FROM node:12-alpine

WORKDIR /app

COPY package.json .

RUN yarn --production

COPY . .

CMD ["yarn", "start"]
