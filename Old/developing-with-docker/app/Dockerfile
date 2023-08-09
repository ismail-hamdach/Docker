FROM node:13-alpine

ENV MONGODB_CONFIG_USERNAME=admin \
    MONGODB_CONFIG_PASSWORD=admin

RUN mkdir -p /home/app

COPY . /home/app

CMD ["node", "/home/app/server.js"]