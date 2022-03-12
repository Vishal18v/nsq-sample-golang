FROM golang:latest

RUN mkdir /producer
WORKDIR /producer
COPY . .
RUN go build -o producer .

CMD ["/producer/producer"]
