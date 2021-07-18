FROM node:12.22-alpine
 


WORKDIR /home/app/

COPY package.json /home/app/


RUN npm install


COPY . /home/app

EXPOSE 3000

CMD [ "npm", "start" ] 