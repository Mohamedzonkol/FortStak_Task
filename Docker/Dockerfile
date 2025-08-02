FROM node:18-alpine

WORKDIR /app

COPY app/package*.json ./
RUN npm install

RUN apk add --no-cache wget

COPY app/ .

EXPOSE 4000

CMD ["node", "index.js"]




