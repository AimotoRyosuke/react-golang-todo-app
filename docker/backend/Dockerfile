FROM golang:alpine
RUN apk update && apk add alpine-sdk
COPY ./backend /app/backend
WORKDIR /app/backend
RUN go mod init todo
RUN go get -u golang.org/x/tools/cmd/goimports
RUN go build -o main .
