FROM node:17
WORKDIR /usr/src/app
COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 8080

CMD ["npm", "start"]
