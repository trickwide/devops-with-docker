# Install Node 16

FROM node:16-alpine

EXPOSE 5000

WORKDIR /usr/src/app

# Copy project files

COPY . .

# Install dependencies

RUN npm install

# Build project

RUN npm run build

# Install serve

RUN npm install -g serve

# Run serve

CMD ["serve", "-s", "-l", "5000", "build"]