# Imagem base
FROM node:18

# Diretório de trabalho dentro do container
WORKDIR /usr/src/app

# Copiar package.json e instalar dependências
COPY package*.json ./
RUN npm install

# Copiar os arquivos do projeto
COPY . .

# Expor a porta
EXPOSE 3001

# Comando para iniciar o app
CMD ["npm", "start"]