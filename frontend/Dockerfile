FROM node:16.5.0-alpine3.14

WORKDIR /app

COPY package*.json /app/

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]