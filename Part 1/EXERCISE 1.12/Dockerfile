FROM node:16.20.0-alpine3.17

EXPOSE 5000

WORKDIR /usr/src/app

COPY . .

RUN npm install

RUN npm install -g serve

RUN npm run build

ENTRYPOINT serve -s -l 5000 build
