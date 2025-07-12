# A basic placeholder Dockerfile
FROM golang:1.18-alpine
WORKDIR /app
COPY . .
RUN go build -o /auth-service
CMD [ "/auth-service" ]
