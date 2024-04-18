# Criando imagem da aplicação
# FROM definir a imagem base | workdir diretorio de trabalho |
FROM node:20.10.0
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
CMD [ "node", "server.js" ]
EXPOSE 8080