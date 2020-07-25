FROM golang:1.14.6-alpine

RUN apk update \
    && apk add --no-cache git bash \
    && go get -u golang.org/x/lint/golint

LABEL golang_version=1.14.6 \
    description="Golang CI image configured with git, bash, and go lint"
    