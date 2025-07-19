# Build React app
FROM node:20-alpine AS build

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

ENV NODE_OPTIONS=--openssl-legacy-provider

# Build React app
RUN npm run build

# Serve with nginx
FROM nginx:alpine

# Copy build output to nginx default html folder
COPY --from=build /app/build /usr/share/nginx/html

# Expose port 80
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]