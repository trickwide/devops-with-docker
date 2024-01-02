# Use Node slim image
FROM node:slim

# Set working directory
WORKDIR /usr/src/app

# Copy current directory to working directory
COPY . .

# Install dependencies
RUN npm install

# Expose port 3000
EXPOSE 3000

# Run the app
CMD ["npm", "run", "dev"]