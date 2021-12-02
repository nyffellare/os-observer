FROM node:16 

WORKDIR /app

COPY package.json /app
RUN npm i --only=production

COPY . .

CMD node app.json
EXPOSE 8080