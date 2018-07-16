FROM golang:latest

RUN go get -u github.com/golang/dep/cmd/dep

WORKDIR /go

CMD ["go", "run", "src/app/main.go"]

