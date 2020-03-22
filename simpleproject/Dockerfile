FROM node:alpine

#if directory is not present it will create it
WORKDIR /usr/app

COPY ./ ./

RUN npm install

CMD ["npm","start"]