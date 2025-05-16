FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=rewat2
ENV MONGODB_PASSWORD=TQJlyj2EQ6hMLPvM
ENV MONGODB_URL=cluster0.qfj4vyk.mongodb.net
ENV MONGODB_NAME=goals-prod

CMD ["npm", "start"]