FROM node:alpine

WORKDIR /product

COPY package.json .

RUN npm install

COPY . .

RUN npm run build

EXPOSE 4002

CMD ["npm", "start"]