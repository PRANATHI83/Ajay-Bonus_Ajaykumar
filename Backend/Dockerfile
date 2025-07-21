FROM node:18

# Set working directory
WORKDIR /app

# Copy dependencies
COPY package*.json ./
RUN npm install

# Copy source files
COPY . .

# Expose backend port
EXPOSE 3529

# Start the server
CMD ["node", "server.js"]

