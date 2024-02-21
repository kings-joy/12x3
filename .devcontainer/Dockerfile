# .devcontainer/Dockerfile

FROM node:14

WORKDIR /workspace

# Copy package.json and yarn.lock to install dependencies
COPY package.json yarn.lock ./

# Install dependencies
RUN yarn install

# Copy the rest of the application code
COPY . .

# Expose the port your Medusa.js backend uses
EXPOSE 9000

CMD ["yarn", "start"]
