FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

ENV MONGO_USERNAME=max
ENV MONGO_PASSWORD=secret

CMD [ "npm", "start" ]

# The Dockerfile is a text file that contains the instructions needed to build a new container image.
