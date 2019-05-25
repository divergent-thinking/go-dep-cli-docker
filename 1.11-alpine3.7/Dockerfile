FROM golang:1.11.10-alpine3.7

RUN apk add --no-cache git \ 
    && go get -u github.com/golang/dep/cmd/dep

WORKDIR /go