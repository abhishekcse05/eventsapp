# Use the slim Node.js base image.
FROM public.ecr.aws/docker/library/node:slim

# Copy application code.
COPY . /app/

# Change the working directory
WORKDIR /app

# Install dependencies.
RUN npm install

# The website listens on port 8080.
EXPOSE 8080

# Start the Express app
CMD ["node", "server.js"]