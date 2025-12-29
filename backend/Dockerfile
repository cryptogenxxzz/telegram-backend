FROM node:20-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install --production
COPY telegram-verification-service.js ./
EXPOSE 3004
CMD ["node", "telegram-verification-service.js"]
