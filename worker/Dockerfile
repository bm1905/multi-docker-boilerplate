# Base image.
FROM node:alpine
# Set work directory.
WORKDIR '/app'
# Copy package file.
COPY ./package.json ./
# Install dependencies.
RUN npm install
# Copy all source code files.
COPY . .
# Startup Command.
CMD ["npm", "run", "start"]