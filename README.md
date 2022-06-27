# Projeto To Do List com Docker! <img src="https://user-images.githubusercontent.com/93009735/176034840-183d8d40-4865-441e-b42c-8dfb5e9662cb.png" alt="image" width="80"/>
Bem vindo ao Docker To Do List!!

Nesse aplicativo, você pode criar sua própria lista de tarefas, adicionando, tirando tarefas que já foram realizadas. Muita praticidade! 

Neste projeto, desenvolvi somente a parte do docker, criando a imagem dockerizada do projeto, o docker compose, os dockers files e a pasta docker commands;

---

# 🐳 Sumário

- [Requisitos do projeto]

  - [1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`]
  - [2. Inicie o container `01container`]
  - [3. Liste os containers filtrando pelo nome `01container`]
  - [4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele]
  - [5. Remova o container `01container` que está em andamento.]
  - [6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.]
  - [7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.]
  - [8. Pare o container `02images` que está em andamento.]
  - [9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.]
  - [10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.]
  - [11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.]
  
 - [Bônus]
   - [12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.]

---

## 🐳 Habilidades desenvolvidas

Neste projeto, fui capaz de:

  - Usar comandos dockers no CLI - Interface de linha de comando;
  - Criar um contêiner Docker para uma aplicação de front-end;
  - Criar um contêiner Docker para uma aplicação de back-end;
  - Criar um contêiner Docker para uma aplicação de testes;
  - Orquestrar os três contêineres utilizando o Docker compose.

---

## 🐳 O que foi desenvolvido

Neste projeto foi desenvolvido uma aplicação Docker! Ao utilizar essa aplicação uma pessoa usuária deverá ser capaz de:

  * Visualizar todos os planetas do sistema solar renderizados na tela;

  * Visualizar todas as cartas com informações sobre missões espaciais;

