FROM node:18.16.1-slim
WORKDIR /app
COPY ./src/package*.json ./
RUN npm install
COPY ./src .
EXPOSE 8080
CMD ["node", "server.js"]
