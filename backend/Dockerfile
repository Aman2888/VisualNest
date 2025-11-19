# Node.js version
FROM node:18-alpine

# Working directory banao
WORKDIR /app

# Package files copy karo
COPY package*.json ./

# Dependencies install karo
RUN npm install

# Saara code copy karo
COPY . .

# Port expose karo (jo tum use kar rahe ho)
EXPOSE 5000

# Start command
CMD ["npm", "start"]