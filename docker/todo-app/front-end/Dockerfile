FROM node:14-alpine AS todofrontend
WORKDIR /
EXPOSE 3000
# Adiciona e descompacta tudo q tem no node modules, assim, não precisa dar npm install
ADD node_modules.tar.gz .
# copia tudo q falta dentro do diretório front end
COPY . .
# depois dele acabou a imagem, é o ultimo comando a ser executado
ENTRYPOINT ["npm", "start"]
