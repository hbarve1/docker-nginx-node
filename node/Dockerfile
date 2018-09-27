
FROM node:8.12.0

RUN mkdir /app
WORKDIR /app

EXPOSE 80

COPY package.json  /app
COPY package-lock.json /app

RUN npm install

COPY . /app

CMD npm run start
