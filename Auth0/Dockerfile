FROM node:18.14.1-alpine

RUN mkdir /app

WORKDIR /app

COPY package.json .

RUN npm install --production

COPY . .

EXPOSE 3000

CMD ["node", "bin/www"]