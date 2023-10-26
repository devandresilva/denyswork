FROM node:latest

RUN apt-get update && apt-get install -y git curl

WORKDIR /app

RUN git clone https://github.com/devandresilva/pokeback.git

WORKDIR /app/pokeback/

RUN npm install

EXPOSE 3000