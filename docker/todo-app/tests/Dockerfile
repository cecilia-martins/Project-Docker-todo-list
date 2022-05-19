# imagem base
FROM mjgargani/puppeteer:trybe1.0
# definição de pasta
WORKDIR /todo-app/tests/

ADD node_modules.tar.gz .
# copia os arquivos p/ container
COPY . . 
# instalação inicial
# RUN npm install
# porta a ser usada
# EXPOSE 3000
# qual comando executar dentro do contêiner
CMD npm test

