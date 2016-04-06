FROM node:latest

RUN git clone https://github.com/scotch-io/node-todo.git

ADD config/database.js /node-todo/config/

WORKDIR /node-todo/

RUN npm install

CMD ["node","server.js"]
