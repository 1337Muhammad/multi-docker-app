FROM node:14.14.0-alpine

WORKDIR "/app"

COPY ./package.json .
RUN npm install

COPY . .

#to run start
CMD ["npm", "run", "start"]
