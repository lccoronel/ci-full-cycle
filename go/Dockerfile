FROM golang:1.19

WORKDIR /app

COPY ./go .

RUN go build -o math

CMD ["./math"]