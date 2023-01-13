FROM node:14-alpine
EXPOSE 3001
ADD node_modules.tar.gz /usr/src/app
COPY . /usr/src/app
ENTRYPOINT [ "npm start" ]