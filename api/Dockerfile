FROM node

WORKDIR /app

COPY package.json .

RUN npm install -g typescript

RUN npm install

COPY . .

RUN tsc

EXPOSE 8080

CMD ["npm", "start"]