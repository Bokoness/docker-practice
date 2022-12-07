# docker build -t node-app .
# docker run -d --name ness -p 3000:3000  node-app

FROM node

WORKDIR /app

COPY . /app

RUN npm install

EXPOSE 80

CMD ["node", "server.js"]
