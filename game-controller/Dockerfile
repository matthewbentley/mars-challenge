# Base image
FROM golang:1.4.2

# Maintainer info
MAINTAINER Adrian Moreno <adrian.moreno@emc.com>

# Get the project
RUN go get github.com/matthewbentley/mars-challenge/game-controller

# Set working directory
WORKDIR /go/src/github.com/matthewbentley/mars-challenge/game-controller

# Expose port
EXPOSE 8080

# Run Game Controller
CMD go run *.go
