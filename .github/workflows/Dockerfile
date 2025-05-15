# Use Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY . .

# Install dependencies
RUN npm install

# Expose the port
EXPOSE 8080

# Start the app
CMD ["npm", "start"]
