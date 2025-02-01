FROM node:13-alpine

ENV MONGO_DB_USERNAME=mongoadmin \
    MONGO_DB_PWD=secret

RUN mkdir -p /home/node-app

COPY ./app_f /home/node-app

CMD ["node", "/home/app/server.js"]