FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# rendre exécutable


EXPOSE 3001

CMD ["node", "api/index.js"]

