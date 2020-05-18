FROM node:10.16.0-alpine
WORKDIR /opt/app
COPY package*.json ./
RUN npm install
EXPOSE 3000
CMD [ "npm", "start"]