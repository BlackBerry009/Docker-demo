FROM node:16

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=root

ENV MONGODB_PASSWORD=123456

CMD ["npm", "start"]