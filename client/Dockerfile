FROM node:lts-alpine

WORKDIR /app
COPY package.json ./
RUN yarn 
COPY README.md ./
COPY src src
COPY public public

CMD yarn run start
