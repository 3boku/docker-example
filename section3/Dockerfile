FROM node:14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

ENV PORT 80

EXPOSE $PORT

VOLUME [ "/app/feedback" ]

CMD ["node", "server.js"]
