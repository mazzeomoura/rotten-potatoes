FROM node
WORKDIR /opt
COPY package*.json /opt
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node","server.js"]
