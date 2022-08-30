FROM        node:lts-alpine
COPY        . ./backend
WORKDIR     /backend
RUN         sleep 120;npm install
CMD         [ "node", "server.js" ]