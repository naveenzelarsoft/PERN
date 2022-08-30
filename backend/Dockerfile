FROM        node:lts-alpine
ADD         https://github.com/ufoscout/docker-compose-wait/releases/download/2.9.0/wait /wait
RUN         chmod +x /wait
COPY        . ./backend
WORKDIR     /backend
RUN         npm install
CMD         /wait && [ "node", "server.js" ]