FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN dnf npm install
ENV REDIS_HOST=redis
    CATALOGUE_HOST=catalogue
    CATALOGUE_PORT=8080
CMD ["node", "server.js"]