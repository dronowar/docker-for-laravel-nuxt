FROM node:18.13.0

RUN mkdir /usr/src/app
WORKDIR /usr/src/app

RUN export NODE_OPTIONS=--openssl-legacy-provider

COPY ./client /usr/src/app

RUN npm install

EXPOSE 3000

ENV NUXT_HOST=0.0.0.0
ENV NUXT_PORT=3000