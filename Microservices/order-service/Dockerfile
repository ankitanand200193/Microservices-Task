FROM node:20-alpine
WORKDIR /order-service
COPY . .
RUN npm install
EXPOSE 3002
CMD['node', 'app.js']