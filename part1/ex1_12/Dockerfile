FROM node:16

EXPOSE 5000

WORKDIR /usr/scr/app

COPY package* ./

RUN npm install

COPY . .

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]