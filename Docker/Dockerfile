FROM node:17

WORKDIR /send

COPY send/package.json ./

RUN yarn

COPY send/. .

CMD ["yarn","start"]