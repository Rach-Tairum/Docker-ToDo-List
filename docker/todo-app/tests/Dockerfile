#depois do as é o nome da aplicação, assim como 
FROM mjgargani/puppeteer:trybe1.0 AS todotests
# quando colocamos o workdir ele automaticamente ja entra na pasta, por isso nas demias pode usar somente o .
WORKDIR /
# Adiciona e descompacta tudo q tem no node modules, assim, não precisa dar npm install
# tar.gz é um arquivo zipado para que todos tenham o mesmo node_modules
ADD node_modules.tar.gz .
# copia tudo q falta dentro do diretório back end
COPY . .
#depois dele acabou a imagem, é o ultimo comando a ser executado
ENTRYPOINT ["npm", "test"]
