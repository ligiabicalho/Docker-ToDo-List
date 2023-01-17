FROM node:14-alpine
WORKDIR /usr/src/app
EXPOSE 3001
ADD node_modules.tar.gz .
COPY . .
# ao determinar uma pasta no WORKDIR, o . em ADD e COPY equivale a pasta do WORKDIR, não precisa repetir.
# caso não seja criada nova pasta no ADD ou COPY, o WORKDIR pode ser omitido.
ENTRYPOINT [ "npm", "start" ]