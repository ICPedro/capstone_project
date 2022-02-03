FROM node:16.13.1-alpine as build
WORKDIR /app
COPY package.json ./
RUN npm install 
#ci --only=production && npm cache clean --force
COPY . .
EXPOSE 3000
CMD "npm" "start"

