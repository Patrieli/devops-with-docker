FROM golang:1.16

COPY ./material-applications/example-backend .

ENV GOPATH=/usr/local/go/bin:$PATH

RUN \
  go build &&\
  go test ./... 

EXPOSE 8080

CMD ["./server"]



