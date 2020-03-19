FROM node:latest

RUN npm install socket.io && \
    npm install node-static

RUN mkdir /streamer

WORKDIR /streamer

COPY index.html ./
COPY server.js ./

CMD node server.js