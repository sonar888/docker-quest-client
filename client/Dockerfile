FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app


COPY package*.json .
RUN npm i

COPY index.html .
COPY vite.config.ts .
COPY src src
COPY public public 

CMD npm run dev