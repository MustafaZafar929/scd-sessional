From node:18

WORKDIR /order-services
COPY package*.json ./

RUN npm install

COPY . .
EXPOSE 3002

CMD [ "node" , "index.js" ]
