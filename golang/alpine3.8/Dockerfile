FROM golang:1.11-alpine3.8

RUN apk update && apk upgrade \
    && apk add --no-cache ca-certificates librdkafka librdkafka-dev pkgconfig gcc musl-dev git
