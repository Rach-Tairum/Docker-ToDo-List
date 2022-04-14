FROM node:14-alpine AS build
WORKDIR /todo-app/back-end
EXPOSE 3001
ADD /node_modules.tar.gz /todo-app/back-end/
COPY . /todo-app/back-end/
#depois dele acabou a imagem, é o ultimo comando a ser executado
ENTRYPOINT [ "npm start" ]