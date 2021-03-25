FROM node:lts-alpine
ADD [".","/src"]
WORKDIR /src
RUN npm install --registry https://registry.npm.taobao.org 

ENTRYPOINT [ "npm","run","start" ]
EXPOSE 3000