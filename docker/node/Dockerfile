FROM node:latest

RUN apt-get update && apt-get install -y git \
	&& rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

WORKDIR /var/www/html
