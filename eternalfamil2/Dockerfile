FROM node:20

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

# index.js yerine main.js olarak güncelledik
CMD [ "node", "main.js" ]
