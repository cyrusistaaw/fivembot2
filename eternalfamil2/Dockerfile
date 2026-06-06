FROM node:20

WORKDIR /usr/src/app

# En dış dizinden eternalfamil2 alt klasörüne bakarak dosyaları kopyala
COPY eternalfamil2/package*.json ./

RUN npm install

# eternalfamil2 klasörünün içindeki main.js ve diğer her şeyi içeri aktar
COPY eternalfamil2/ .

# Botu tetikle
CMD [ "node", "main.js" ]
