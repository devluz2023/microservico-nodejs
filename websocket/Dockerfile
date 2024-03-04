# Use the official Node.js 14 image
FROM node:14

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 3000

# Command to run the application
CMD ["node", "src/servidor.js"]
# CMD ["/bin/sh", "-c", "while true; do sleep 3600; done > /dev/null"]
