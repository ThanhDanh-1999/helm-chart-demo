from node:8-alpine
# create  app directory
WORKDIR /usr/node/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080 
CMD ["npm","test"]