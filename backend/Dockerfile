FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
# Cài đặt thư viện
RUN npm install
# Copy toàn bộ code còn lại vào
COPY . .
# Mở cổng
EXPOSE 3000
# Chạy file server.js
CMD ["node", "server.js"]