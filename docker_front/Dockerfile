FROM nginx:latest

RUN apt-get update && apt-get install -y git

WORKDIR /usr/share/nginx/html/app

RUN git clone https://github.com/devandresilva/pokefront.git .

RUN git pull

EXPOSE 80