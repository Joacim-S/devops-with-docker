FROM golang

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

ENV REQUEST_ORIGIN=http://localhost:8080

RUN go build

CMD ["./server"]