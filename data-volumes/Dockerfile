FROM fs

WORKDIR /app

COPY pachage.json /app

RUN npm install

COPY . /app

CMD ["node", "server.js"]