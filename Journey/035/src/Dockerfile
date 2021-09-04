FROM node:16-alpine3.11

WORKDIR /usr/app

# Install dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default Command
CMD ["npm", "start"]