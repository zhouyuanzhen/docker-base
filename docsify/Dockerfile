FROM node:24-slim

LABEL description="Dockerfile for build my Docsify docker container."

WORKDIR /docs

RUN npm install -g docsify-cli@latest

EXPOSE 3000/tcp

ENTRYPOINT ["docsify", "serve", "."]
