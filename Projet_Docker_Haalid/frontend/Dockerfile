FROM node:alpine as builder
WORKDIR /frontend
COPY ./package.json /frontend
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm", "run", "start" ]
