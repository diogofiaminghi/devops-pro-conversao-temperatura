# a linha abaixo, pega a imagem base do node diretamente
# do Docker Hub
FROM node
WORKDIR /workdir-dockerfile
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]
