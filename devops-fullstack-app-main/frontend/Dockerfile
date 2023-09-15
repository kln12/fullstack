# Use the official Node.js 14.17.0 image as a base image
FROM node:14.17.0

# Set the working directory inside the container
WORKDIR /app

# Copy package.json and package-lock.json to install dependencies
COPY package*.json ./

# Install frontend dependencies
RUN npm install

# Copy the frontend source code into the container
COPY . .

# Expose port 3000 for the frontend
EXPOSE 3000

# Define the command to start the frontend application
CMD ["npm", "start"]
