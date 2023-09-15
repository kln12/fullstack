# Use the official Golang 1.19 image as a base image
FROM golang:1.19

# Set the working directory inside the container
WORKDIR /app

# Copy the backend source code into the container
COPY . .

# Build the backend application
RUN go build

# Expose port 8080 for the backend
EXPOSE 8080

# Define the command to start the backend application
CMD ["./main"]
