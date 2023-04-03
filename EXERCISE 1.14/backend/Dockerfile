FROM golang:1.16.15-alpine3.15

EXPOSE 8000

WORKDIR /usr/src/app

COPY . .

ENV PORT=8000

ENV REQUEST_ORIGIN=http://localhost:5000

RUN go build

ENTRYPOINT ./server
