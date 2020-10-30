# Imagem de Origem
FROM node:10.23
# Diretório de trabalho(é onde a aplicação ficará dentro do container).
WORKDIR /app

# Instalando dependências da aplicação e armazenando em cache.
COPY package*.json ./
RUN ls
RUN npm install 
RUN npm install react-scripts gulp -g 
COPY . .
# start app
CMD ["npm", "start"]