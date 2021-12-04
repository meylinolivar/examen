FROM node:16.8.0

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY ./ ./

ENV API_PORT=5000

EXPOSE 5000

CMD ["npm", "run", "start"]