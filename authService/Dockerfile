FROM node:18.12-slim

WORKDIR /app

COPY ["package.json", "yarn.lock", "./"]

RUN yarn

COPY . .

CMD [ "node", "app.js" ]