FROM node:14.15.4

WORKDIR /src

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm", "run", "serve"]