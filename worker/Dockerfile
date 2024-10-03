FROM node:14.14.0-alpine

WORKDIR "/app"

COPY ./package.json .
RUN npm install

COPY . .

#to start project on prod
CMD ["npm", "run", "start"]
