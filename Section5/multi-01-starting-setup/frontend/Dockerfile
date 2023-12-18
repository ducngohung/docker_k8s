FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOST 3000

CMD ["npm", "start"]