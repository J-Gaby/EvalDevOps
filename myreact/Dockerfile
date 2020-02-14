FROM node:latest

WORKDIR /app/myreact

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm","start"]