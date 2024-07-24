FROM node:alpine

WORKDIR /frontend
# Copy package.json and package-lock.json to the working directory
COPY package.json ./
RUN npm install

COPY . .


CMD ["npm", "run", "build"]