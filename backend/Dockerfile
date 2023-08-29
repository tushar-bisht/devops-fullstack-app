FROM golang:1.19-alpine
WORKDIR /backend/
COPY . .
RUN go get 
EXPOSE 8080
CMD ["go", "run", "main.go"]
