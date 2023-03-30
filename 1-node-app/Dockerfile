# KOMUT ARGUMAN

#docker pull ubuntu:18.04
#docker run -it ubuntu:18.04
FROM ubuntu:18.04

#apt-get update
RUN apt-get update

#apt-get install curl -y
RUN apt-get install curl -y

#curl -sL https://deb.nodesource.com/setup_10.x | bash
RUN curl -sL https://deb.nodesource.com/setup_10.x | bash

#apt-get install nodejs -y
RUN apt-get install nodejs -y

#cd opt
#mkdir node-app
WORKDIR /opt/node-app
COPY . /opt/node-app/

ENV channel=talha


CMD ["node","index.js"];

