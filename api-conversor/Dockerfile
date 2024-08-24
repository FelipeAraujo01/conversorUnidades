# Use uma imagem oficial do Node.js como base
FROM node:18-alpine

# Defina o diretório de trabalho no contêiner
WORKDIR /app

# Copie o package.json e o package-lock.json
COPY package*.json ./

# Instale as dependências do projeto
RUN npm install

# Copie o restante dos arquivos da aplicação
COPY . .

# Exponha a porta que a aplicação usará (ex: 3000)
EXPOSE 3000

# Comando para rodar a aplicação NestJS
CMD ["npm", "run", "start:prod"]
