FROM golang:1.18-bullseye AS build

WORKDIR /app
COPY main.go /app
RUN go build -o /usr/local/bin/apm-server .

CMD apm-server
