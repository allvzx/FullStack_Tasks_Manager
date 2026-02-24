# ---- Base ----
FROM node:18-alpine

WORKDIR /app

# Install dependencies
COPY package*.json ./
RUN npm install --production

# Copy source
COPY . .

# Expose API port
EXPOSE 5000

ENV NODE_ENV=production

CMD ["node", "server.js"]
