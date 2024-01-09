# Use an official Node.js runtime as a parent image
FROM node:latest

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy package files to the working directory
COPY package*.json ./

# Install app dependencies
RUN npm install

# Copy the application code to the container
COPY . .

# Expose the port your Node.js app is running on
EXPOSE 3000

# Command to run the application
CMD ["npm", "start"]
