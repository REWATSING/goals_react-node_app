FROM node:18

WORKDIR /app

COPY package.json .

RUN npm install --include=dev

RUN npm install -g nodemon 

COPY . .

EXPOSE 80

CMD ["npm", "start"]