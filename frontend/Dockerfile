FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .    
EXPOSE 3000  
CMD ["npm", "start"] 
# This Dockerfile sets up a Node.js environment for a frontend application using Node.js version 18 on an Alpine Linux base image.  
# It sets the working directory to /app, copies the package.json and package-lock.json files, installs the dependencies,
# copies the rest of the application code, exposes port 3000, and starts the application using the npm start command.
# To build the Docker image, use the command: docker build -t frontend-app .