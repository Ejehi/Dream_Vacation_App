FROM node:slim

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Use environment variable for PORT
ENV PORT=3001

EXPOSE 3001

CMD ["node", "server.js"]
