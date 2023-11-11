FROM node:16

WORKDIR app/backend

COPY package*.json ./

RUN npm i

COPY . .

EXPOSE 8888

CMD ["npm","run","dev"]
