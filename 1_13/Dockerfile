FROM golang:1.16

WORKDIR /mydir

COPY . .

RUN go build

EXPOSE 8080

CMD ["./server"]
