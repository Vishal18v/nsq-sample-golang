FROM golang:latest

RUN mkdir /consumer
WORKDIR /consumer
COPY . .
RUN go build -o consumer .

CMD ["/consumer/consumer"]
