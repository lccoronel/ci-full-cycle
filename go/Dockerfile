FROM golang:1.19

WORKDIR /app

COPY . .

RUN ls
RUN go build -o math

CMD ["./math"]