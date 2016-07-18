FROM node:wheezy

WORKDIR /var/www/app

RUN npm install -g nodemon
RUN npm install

EXPOSE 3000

CMD ["nodemon", "-L", "server.js"]
