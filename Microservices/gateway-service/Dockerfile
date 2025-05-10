FROM node:20-alpine
WORKDIR /gateway-service
COPY . .
RUN npm install
EXPOSE 3003
CMD['node', 'app.js']