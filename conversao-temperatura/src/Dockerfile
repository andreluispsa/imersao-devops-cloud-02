FROM node:18.16.0
# WORKDIR basicamente é similar a
# mkdir /app
# cd /app
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
# expõe uma porta para a execução da aplicação
EXPOSE 8080
CMD ["node", "server.js"]
