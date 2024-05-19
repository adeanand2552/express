# Official Node.js image as a base
FROM node:14

# Working directory
WORKDIR /usr/src/app

# Copy the package.json file
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port
EXPOSE 8080

# run the application
CMD ["node", "index.js"]
