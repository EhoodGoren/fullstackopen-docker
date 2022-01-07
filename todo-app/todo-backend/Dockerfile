FROM node:16

USER node
  
WORKDIR /usr/src/app

COPY . .

RUN npm ci 

ENV DEBUG=playground:*

EXPOSE 3000

CMD npm start