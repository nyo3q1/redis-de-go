FROM golang:1.13

WORKDIR /app
COPY . .
RUN go build -o redis_sample

CMD ["./redis_sample"]