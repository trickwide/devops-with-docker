# Install Go 1.16

FROM golang:1.16-alpine

EXPOSE 8080

WORKDIR /usr/src/app

# Copy project files

COPY . .

# Build project

RUN go build

# Run project

CMD ["./server"]



