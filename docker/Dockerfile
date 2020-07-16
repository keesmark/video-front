FROM node:12.13.0-alpine

WORKDIR /app

RUN apk update && \
  apk upgrade && \
  npm install nuxt create-nuxt-app

ENV HOST 0.0.0.0

EXPOSE 3000