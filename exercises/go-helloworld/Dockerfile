FROM golang:alpine
LABEL maintainer="Jorge Barrera"

WORKDIR /go/src/app
ADD . .
RUN go mod init
RUN go build -o helloworld
EXPOSE 6111

# command to run on container start
CMD ["./helloworld"]