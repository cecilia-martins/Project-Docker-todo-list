# imagem base
FROM node:14-alpine
# definição de pasta
WORKDIR /todo-app/back-end/

ADD node_modules.tar.gz .
# copia os arquivos p/ container
COPY . . 
# instalação inicial
# RUN npm install
# porta a ser usada
EXPOSE 3001
# qual comando executar dentro do contêiner
ENTRYPOINT ["npm", "start"]