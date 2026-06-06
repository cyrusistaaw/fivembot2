FROM node:20

WORKDIR /usr/src/app

# Dosyaları eternalfamil2 alt klasöründen çekmesini söylüyoruz
COPY eternalfamil2/package*.json ./

RUN npm install

COPY eternalfamil2/ .

CMD [ "node", "index.js" ]
