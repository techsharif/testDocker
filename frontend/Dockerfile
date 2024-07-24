FROM node:alpine

WORKDIR /frontend
COPY . .
# Copy package.json and package-lock.json to the working directory
COPY ./frontend/package.json ./frontend/package-lock.json ./
RUN npm install

CMD ["npm", "run", "build"]