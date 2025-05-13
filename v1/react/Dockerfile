FROM node:16-alpine3.11

WORKDIR /usr/src/app

ADD ./app /usr/src/app

RUN yarn install

CMD ["yarn", "start"]