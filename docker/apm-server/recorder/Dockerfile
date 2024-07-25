FROM golang:1.23rc2 AS build

WORKDIR /app
COPY main.go /app
RUN go build -o /usr/local/bin/apm-server .

CMD apm-server
