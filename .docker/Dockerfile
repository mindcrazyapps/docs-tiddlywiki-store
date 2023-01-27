FROM node:8.12-alpine

RUN apk add --no-cache tini && npm install -g docsify-cli@latest

WORKDIR /docs

EXPOSE 3000

ENTRYPOINT ["/sbin/tini", "--"]
CMD [ "docsify", "serve", "." ]
