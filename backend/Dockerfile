# Use the official Node.js 14 image as the base image
FROM node:16-alpine

# Set the working directory inside the container
WORKDIR /app/backend

# Copy package.json and package-lock.json to the working directory
#COPY package*.json .

# Install dependencies
#RUN npm install

# Copy the rest of the application code into the container
COPY . .

# Expose the port on which the application will run
EXPOSE 5000

# Command to run the application
CMD ["node", "app.js"]
