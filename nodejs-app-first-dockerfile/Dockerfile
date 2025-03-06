FROM node

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 80  

CMD ["node", "server.js"]

#docker build -t my-node-app .
#docker run -it -p 3000:80 my-node-app
#docker images