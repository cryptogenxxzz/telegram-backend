FROM node:20-alpine
WORKDIR /app
COPY backend/package*.json ./
RUN npm install --production
COPY backend/telegram-verification-service.js ./
EXPOSE 3004
CMD ["node", "telegram-verification-service.js"]
