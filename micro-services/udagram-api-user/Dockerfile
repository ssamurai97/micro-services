FROM node:14


WORKDIR /src/app 

COPY package*.json ./


RUN npm ci


COPY . .

EXPOSE 8080

CMD ["npm", "run", "prod"]


