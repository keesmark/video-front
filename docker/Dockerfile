FROM node:12.13.0-alpine

WORKDIR /app

RUN apk update && \
    apk upgrade && \
    npm install -g nuxt \
    npm install -g create-nuxt-app

ENV HOST 0.0.0.0

EXPOSE 3000