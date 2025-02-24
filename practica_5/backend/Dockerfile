FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

CMD [ "node", "app.js" ]

# The Dockerfile is a text file that contains the instructions needed to build a new container image.
