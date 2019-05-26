FROM golang:1.11.10-stretch

RUN apt-get update \
    && apt-get install git \
    && go get -u github.com/golang/dep/cmd/dep

WORKDIR /go

ADD dep.sh .

ENTRYPOINT ["sh", "dep.sh"]