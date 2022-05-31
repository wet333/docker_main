FROM ubuntu:20.04

SHELL ["/bin/bash", "-c"]
ENV DEBIAN_FRONTEND noninteractive

RUN apt update
RUN apt install -y git
RUN apt install -y curl
RUN apt install -y nginx

ADD ./index.html /var/www/html/index.html