# a linha abaixo, pega a imagem base do node diretamente
# do Docker Hub
FROM node:18.16.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]