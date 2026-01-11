FROM node:20-alpine

WORKDIR /usr/src/

COPY ./package*.json ./

RUN npm ci

COPY ./ ./

EXPOSE 3000

CMD ["npm", "start"]
