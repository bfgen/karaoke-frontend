FROM node:16

WORKDIR /application

ADD . /application

RUN npm install

ENTRYPOINT ["npm", "run", "serve"]
