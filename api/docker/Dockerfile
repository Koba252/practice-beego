FROM golang:1.18.3-alpine3.16

ENV ROOT /go
ENV CGO_ENABLED 0

WORKDIR ${ROOT}

RUN apk update && apk add --no-cache git
