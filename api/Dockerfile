FROM node:17-alpine

RUN npm install -g nodemon

WORKDIR /app

COPY . /app

COPY package.json .

RUN npm install

EXPOSE 4000

CMD ["npm", "run", "dev"]