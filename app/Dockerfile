FROM node:12.22-alpine
EXPOSE 3000 4200


WORKDIR /home/app/

COPY package.json /home/app/
COPY package.lock.json /home/app/

RUN npm install
RUN npm start

COPY . /home/app
