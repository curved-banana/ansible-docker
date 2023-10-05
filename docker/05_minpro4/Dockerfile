FROM golang:1.19

RUN go get -d github.com/hashicorp/learn-go-webapp-demo
WORKDIR /go/pkg/mod/github.com/hashicorp/learn-go-webapp-demo@v0.0.0-20230113184849-2801371511c4

EXPOSE 8080
CMD go run webapp.go