FROM golang:1.12.5-stretch

RUN apt-get update \
    && apt-get install git \
    && go get -u github.com/golang/dep/cmd/dep

WORKDIR /go