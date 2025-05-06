
# React UI Dockerfile

# Use official Node.js image as a base
FROM node:16

# Set working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package*.json ./
RUN npm install

# Copy the application source code
COPY . .

# Expose port and run the application
EXPOSE 3000
CMD ["npm", "run", "dev"]
