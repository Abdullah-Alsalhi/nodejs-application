FROM node:10-alpine

WORKDIR /home/node/app

ADD . /home/node/app

RUN npm install 

EXPOSE 3001

CMD [ "node", "index.js" ]
