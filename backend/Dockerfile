# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy dependency files and install packages
COPY package*.json ./
RUN npm install

# Copy remaining files
COPY . .

# Expose backend port
EXPOSE 5000

# Start the server
CMD ["npm", "start"]
