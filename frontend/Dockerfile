FROM node:latest

WORKDIR /usr/app

COPY ./frontend/package.json .

RUN npm install

COPY ./frontend .

EXPOSE 3000

CMD [ "npm", "start" ]