#depois do as é o nome da aplicação, assim como 
FROM node:14-alpine AS todobackend
WORKDIR /
# expoe a porta 3001 do host
EXPOSE 3001
# Adiciona e descompacta tudo q tem no node modules, assim, não precisa dar npm install
ADD /node_modules.tar.gz .
# copia tudo q falta dentro do diretório back end
COPY . .
#depois dele acabou a imagem, é o ultimo comando a ser executado
ENTRYPOINT [ "npm start" ]